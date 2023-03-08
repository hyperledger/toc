# Maintainers

A sample MAINTAINERS.md file for a Hyperledger project repository. Feel free to
copy this file into your repository and update it for your specific needs.

## Maintainer Scopes, GitHub Roles and GitHub Teams

The only Maintainer scope for this repository is `Maintainer`, which is given to all repository maintainers. The "Maintainer" scope uses the `Maintain` [GitHub Role](https://docs.github.com/en/organizations/managing-user-access-to-your-organizations-repositories/repository-roles-for-an-organization).

The GitHub teams for this repository are:

- Maintainer: [\<repo name> committers](#)

## Active Maintainers

<!-- Please keep this sorted alphabetically by github -->

| Name             | Github           |
| ---------------- | ---------------- |
|                  |                  |

## Emeritus Maintainers

| Name             | Github           |
| ---------------- | ---------------- |
|                  |                  |

## The Duties of a Maintainer

Maintainers are expected to perform the following tasks for this repository. The tasks are listed in more or less priority order:

- Review, provide feedback on, and merge or reject GitHub Pull Requests from
  Contributors.
- Review, triage, comment on, and, when appropriate, close GitHub Issues
  submitted by Contributors.
- When appropriate, lead/facilitate architectural discussions in the community.
- When appropriate, lead/facilitate the creation of a product roadmap.
- Ensure that there is a well defined (and ideally automated) product test and
  release pipeline, including the publication of release artifacts.
- When appropriate, execute the product release process.
- Maintain the repository CONTRIBUTING.md file and getting started documents to
  give guidance and encouragement to those wanting to contribute to the product, and those wanting to become maintainers.
- Contribute to the product via GitHub Pull Requests.
- Monitor requests from the Hyperledger Technical Oversight Committee about the
contents and management of Hyperledger repositories, such as branch handling,
required files in repositories and so on.
- Contribute to the Hyperledger Project's Quarterly Report.

## Becoming a Maintainer

This community welcomes contributions. Interested contributors are encouraged to
progress to become maintainers. To become a maintainer the following steps
occur, roughly in order.

- The proposed maintainer establishes their reputation in the community,
  including authoring five (5) significant merged pull requests, and expresses
  an interest in becoming a maintainer for the repository.
- A PR is created to update this file to add the proposed maintainer to the list of active maintainers.
- The PR is authored by an existing maintainer or has a comment on the PR from an existing maintainer supporting the proposal.
- The PR is authored by the proposed maintainer or has a comment on the PR from the proposed maintainer expressing their interest in being a maintainer.
  - The PR or comment from the proposed maintainer must include their
    willingness to be a long-term (more than 6 month) maintainer.
- Once the PR and necessary comments have been received, an approval timeframe begins.
- The PR **MUST** be communicated on all appropriate communication channels, including relevant community calls, chat channels and mailing lists. Comments of support from the community are welcome.
- An add maintainer PR may be vetoed by another maintainer prior to merging.
  - Vetoes must be accompanied by a public explanation as a comment in the
    PR.
  - The explanation of the veto must be reasonable.
  - A veto can be retracted. In that case the approval/veto timeframe is reset.
  - It is bad form to veto, retract, and veto again.
- The PR is merged and the proposed maintainer becomes a maintainer if
  - No maintainer posts a veto AND
    - Either: Two weeks have passed since at least 3 Maintainer PR approvals has been recorded, OR
    - An absolute majority of maintainers have approved the PR.
- Once the add maintainer PR has been merged, any necessary updates to the GitHub Teams are made.

## Removing Maintainers

Being a maintainer is not a status symbol or a title to be carried
indefinitely. It will occasionally be necessary and appropriate to move a
maintainer to emeritus status. This can occur in the following situations:

- Resignation of a maintainer.
- Violation of the Code of Conduct warranting removal.
- Inactivity.
  - A general measure of inactivity will be no commits or code review comments
    for one reporting quarter. This will not be strictly enforced if
    the maintainer expresses a reasonable intent to continue contributing.
  - Reasonable exceptions to inactivity will be granted for known long term
    leave such as parental leave and medical leave.
- Other circumstances at the discretion of the other Maintainers.

The process to move a maintainer from active to emeritus status is comparable to the process for adding a maintainer, outlined above. In the case of voluntary
resignation, the Pull Request can be merged following a maintainer PR approval. If the removal is for any other reason, the following steps **SHOULD** be followed:

- A PR is created to update this file to move the maintainer to the list of emeritus maintainers.
- The PR is authored by an existing maintainer or has a comment on the PR from an existing maintainer supporting the proposal.
- Once the PR and necessary comments have been received, the approval timeframe begins.
- The PR **MAY** be communicated on appropriate communication channels, including relevant community calls, chat channels and mailing lists.
- The PR may be vetoed prior to merging by a maintainer other than the one to be removed.
  - Vetoes must be accompanied by a public explanation of the veto.
  - The explanation of the veto must be reasonable.
  - A veto can be retracted. In that case the approval/veto timeframe is reset.
  - It is bad form to veto, retract, and veto again.
- The PR is merged and the maintainer transitions to maintainer emeritus if:
  - No maintainer posts a veto AND
    - Either: Two weeks have passed since the minimum number of PR approvals has been recorded, OR
    - An absolute majority of maintainers have approved the PR.

Returning to active status from emeritus status uses the same steps as adding a
new maintainer. Note that the emeritus maintainer already has the 5 required
significant changes as there is no contribution time horizon for those.
