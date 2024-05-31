# Best Practices For Automation Pipelines<!-- omit in toc -->

- [Version Control Systems](#version-control-systems)
- [Documentation Publishing](#documentation-publishing)
- [Static analysis aka Static Application Security Testing (SAST)](#static-analysis-aka-static-application-security-testing-sast)
- [Software Composition Analysis dependency scans and/or setup Dependabot in Settings/Security](#software-composition-analysis-dependency-scans-andor-setup-dependabot-in-settingssecurity)
- [GitHub Actions](#github-actions)
- [Contribution Flow](#contribution-flow)


## Version Control Systems

1. Use git and GitHub
2. Protect code branches. In GitHub settings "Branch protection rules" select:

    - "Require a pull request before merging"
    - "Require approvals": https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches#require-pull-request-reviews-before-merging  
    - "Require status checks to pass before merging": https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/managing-protected-branches/about-protected-branches#require-status-checks-before-merging

GitHub Actions is the preferred CI platform to implement checks. Create a test pipeline, consider required checks for:
1. DCO (required) https://github.com/apps/dco
2. Linters
3. Linting GitHub Action workflow .yaml Files: https://github.com/rhysd/actionlint
4. Unit tests
5. Integration tests
6. Code coverage

## Documentation Publishing

- Consider building and deploying the documentation through the CI/CD pipeline
- Prefer choosing a documentation generator/template instead of writing it from scratch
- Consider a documentation organization that handles git tags in  way that readers can select which tag/release they would like to view the documentation for.

Examples: 

- The recommended template for documentation: https://github.com/hyperledger-labs/documentation-template
- ReadTheDocs webhook: https://docs.readthedocs.io/en/stable/integrations.html

## Static analysis aka Static Application Security Testing (SAST)
- Consider performing automated SAST scans to protect your app from security risks.

Examples:

- CodeQL: https://docs.github.com/en/code-security/code-scanning/automatically-scanning-your-code-for-vulnerabilities-and-errors/about-code-scanning-with-codeql
- Snyk: https://docs.snyk.io/integrations/git-repository-scm-integrations/github-integration

The upside of CodeQL is that it's a built-in feature of GitHub so it definitely has the lowest barrier to entry/easiest and quickest setup. 
Whether it's actually the best tool for your project will depend on a list of factors such as the programming language being used, what are the build-system(s) in place, etc.

## Software Composition Analysis dependency scans and/or setup Dependabot in Settings/Security

- Consider performing automated [software composition analysis](https://en.wikipedia.org/wiki/Software_composition_analysis) to manage open source risk.

- Dependabot: https://docs.github.com/en/code-security/dependabot/dependabot-security-updates/configuring-dependabot-security-updates

- Trivy: https://github.com/aquasecurity/trivy
    It supports pom.xml files but not build.gradle files. If you have a Gradle project you can use the Maven Publish Gradle plugin to generate an equivalent pom.xml file.

## GitHub Actions

Note: use Reusable GitHub actions to reduce the number of top-level checks
https://docs.github.com/en/actions/using-workflows/reusing-workflows

- Monitor GitHub Actions success rate, usage metrics and many other statistics about billing hours here: - https://app.octolense.com/accounts/hyperledger
- Use GitHub Actions efficiently and reduce unnecessary runner usage:
- Use cancel-in-progress to suppress multiple jobs for multiple pushes to the same pull request
https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions#example-using-concurrency-to-cancel-any-in-progress-job-or-run
- Uncheck branch protection rule "Require branches to be up to date before merging" to reduce number of runs
    * Potentially add a scheduled run if you are concerned about incompatible PRs getting merged
    * You can enable this via built-in GitHub YAML syntax:
        https://docs.github.com/en/repositories/configuring-branches-and-merges-in-your-repository/defining-the-mergeability-of-pull-requests/about-protected-branches#require-status-checks-before-merging


- Use path filters to eliminate unnecessary runs either 
  * through the built-in GitHub Action YAML syntax: https://docs.github.com/en/actions/using-workflows/workflow-syntax-for-github-actions#filter-pattern-cheat-sheet
  
  * or by using a third-party GitHub Action: https://github.com/dorny/paths-filter

## Contribution Flow

- Documentation pull-requests shouldn’t require building and testing code, so that people who only want to commit a documentation change can do it without having to
set up a full-blown development environment.
- Consider custom docker images for CI with pre-installed and pre-configured dependencies
- Consider running some jobs on schedule (nightly) rather than on each pull request (e.g. full matrix of platform tests, expensive security scans, code coverage)
- Inspect Github Actions run results on your own fork prior to opening Pull Request
The simplest way to do this is to simply open the pull request for your own fork's main branch the same way as you would open it for the upstream repository's.
Contact Hyperledger staff for the possibility of dedicated paid runners
- Consider using development container images which come pre-installed with all the dependencies a contributor need to get started with writing code on the project.
https://code.visualstudio.com/docs/devcontainers/containers
- Consider leveraging pre-commit hooks via tools like husky (NodeJS) and lint-staged which can run arbitrary scripts at the time of you making a git commit.
    * https://www.npmjs.com/package/lint-staged
    * https://www.npmjs.com/package/husky
    * https://www.npmjs.com/package/@commitlint/cli
- Encourage developers to run tests locally before opening a pull request.
- If due to technical constraints it is not possible to run the tests locally at all, the next best thing to encourage contributors is to run the CI on their personal fork (submit a PR against their their personal fork's main branch first while drafting the PR). Once the tests are passing on their fork's CI, they are ready to open the PR for review on the upstream repository.
- Document how to run tests locally
- Document how to run individual failing tests
- Document how to add tests of all types.
