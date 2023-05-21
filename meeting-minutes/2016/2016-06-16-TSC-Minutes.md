---
layout: default
title: 2016 06 16 TSC Minutes
parent: 2016
grand_parent: Meeting Minutes
---
# 2016 06 16 TSC Minutes

**Hyperledger Project**

Technical Steering Committee (TSC) Meeting

June 16, 2016 (7:00am - 8:30am PT)via GoToMeeting

**TSC Members**



| Name                 |  Company           | Present    |
|-----------------------|-----------------------|-----|
| Emmanuel Viale        | Accenture             | Yes |
| Stan Liberman         | CME Group             | Yes |
| Tamas Blummer         | Digital Asset         | Yes |
| Stefan Teis           | Deutsche Boerse Group | Yes |
| Pardha Vishnumolakala | DTCC                  | Yes |
| Hart Montgomery       | Fujitsu               | Yes |
| Satoshi Oshima        | Hitachi               | Yes |
| Chris Ferris          | IBM                   | Yes |
| Mic Bowman            | Intel                 | Yes |
| David Voell           | J.P. Morgan           | Yes |
| Richard G. Brown      | R3                    | Yes |

  

**Resources:**

- Github: 
  <a href="http://www.github.com/hyperledger" class="external-link"
  rel="nofollow"><span>www.github.com/hyperledger</span></a>
- Wiki:  <a href="https://github.com/hyperledger/hyperledger/wiki"
  class="external-link"
  rel="nofollow">https://github.com/hyperledger/hyperledger/wiki</a>
- IRC:  \#hyperledger on
  <a href="http://freenode.net" class="external-link"
  rel="nofollow">freenode.net</a> (has Meetbot)
- Public lists: 
  <a href="http://lists.hyperledger.org" class="external-link"
  rel="nofollow">lists.hyperledger.org</a>
- Slack:  <a href="https://slack.hyperledger.org/" class="external-link"
  rel="nofollow"><span>https://slack.hyperledger.org/</span></a>
  (self-generated invites)
- Information on the TSC Members can be found at
  <a href="https://www.hyperledger.org/about/tsc" class="external-link"
  rel="nofollow"><span>https://www.hyperledger.org/about/tsc</span></a>
- Meetings:  <a
  href="https://github.com/hyperledger/hyperledger/wiki/PublicMeetingCalendar"
  class="external-link"
  rel="nofollow">https://github.com/hyperledger/hyperledger/wiki/PublicMeetingCalendar</a>

  

**Agenda**

- Action Item review
- <a
  href="https://docs.google.com/document/d/1ROq44KpxuelkOp8GpceFNcv8K6XfWdaOnknzBk73OMc/edit"
  class="external-link" rel="nofollow"><span>Virtual Hackathon</span></a>
  Update (Dan Middleton)
- HIP identifier: Proposal to include
  <a href="https://github.com/ghaskins/chaintool" class="external-link"
  rel="nofollow"><span>chaintool</span></a> project repository in
  hyperledger/fabric (Greg Haskins)
- WG Updates

  

**Action Item Review**

- Exit criteria <a
  href="https://docs.google.com/document/d/1hmZY5LnZydTiYmkbtwyEYEkHEsSedlUhJbnlXGFrEP0/edit#heading=h.f4lv7usw6jp5"
  class="external-link" rel="nofollow"><span>summary</span></a> (Arnaud
  Le Hors)

- - Discussion

  - - Jeremy Sevareid provided an overview of the table added to page 3
      of the exit criteria <a
      href="https://docs.google.com/document/d/1hmZY5LnZydTiYmkbtwyEYEkHEsSedlUhJbnlXGFrEP0/edit#heading=h.f4lv7usw6jp5"
      class="external-link" rel="nofollow"><span>summary doc</span></a>,
      noting a preference that the Project should have a definition of
      “done.”

    - MD:  If this helps add context, "done" is usually handled in most
      of our projects in release management. Incubation is normally a
      measure of whether there are people actually working on the
      project and following the rules. Some projects have an incubation
      exit criteria of "participating in two releases" to ensure there
      is also something "done" (again, done being determined in the
      release process)

    - CF:  Maybe a release yardstick for something that we are going to
      consider being ready for primetime.  But, exit from incubation
      should not be predicated on if something if “release ready”

    - Hart:  People are worried that outsiders will equate “maturation”
      with a product that is ready to use; someone might use it before
      it is ready.

    - Brian B:  These observations are very insightful.  Separate out 2
      things -- maturity and ongoing health of community (that is this
      exit criteria) put out a release that represents the community. 
      As well as ongoing reporting process that should go up to TSC
      (releases, new contributors, code quality, bugs outstanding, not
      just metrics, but also narrative).  Being able to respond to
      security notices and respond timely. Separately, question of code
      maturity and labeling, would like to see consistent naming
      protocol (developer preview, alpha, beta, production, etc.)

    - RGB:  this is very helpful.  Does ASF have a document that we
      could use so we don’t have to reinvent?

    - - Brian B:  Yes, <a
        href="http://incubator.apache.org/incubation/Incubation_Policy.html#Graduating+from+the+Incubator"
        class="external-link" rel="nofollow"><span>here</span></a>. 
        Hyperledger Project may want to add release taxonomy.
      - CF:  Fabric team was hoping to cut a release, don’t need to call
        it anything.  Would like to demonstrate that you can produce a
        release as a team (established process, etc.)  Do we need to
        wait until we see release criteria, or can we just release and
        call alpha?
      - Brian B:  Don’t want to hold up a release for taxonomy… but
        taxonomy doesn’t take long to do.  Might also be useful when
        making release to highlight key things (i.e. if performance may
        be a concern)
      - CF:  Call to action -- can people weigh in with comments in the
        Google doc so we don’t have to wait for a weekly call.
      - ACTION:  Arnaud to take another pass on exit criteria and send
        to list.
      - ACTION:  Brian to pull together first draft of release taxonomy
        in parallel to exit criteria

- Hackathons

- - \[June\] Recap later in TSC Meeting

  - \[July\] Review 2 options (week of 7/25)

  - - Will distribution options via separate thread.

  - \[August\] Virtual
    (<a href="http://doodle.com/poll/r4ftyyvshef2rn6z" class="external-link"
    rel="nofollow"><span>http://doodle.com/poll/r4ftyyvshef2rn6z</span></a>)

  - \[September/October\] Discuss Amsterdam at ABN AMRO
    (<a href="http://doodle.com/poll/y9h2e497essf9pg9" class="external-link"
    rel="nofollow"><span>http://doodle.com/poll/y9h2e497essf9pg9</span></a>)

  - - Lots of interest in area -- IBM NL, Holland Fintech Community,
      Blockchain initiative of the Dutch Government, Amsterdam City and
      the Tech University of Delft. Good network and lots of blockchain
      contributors in Amsterdam (incl Ethereum).

- Sibos, Geneva, September 26-29

- - From the Marketing Committee:  "This is a significant marketing
    opportunity and as such we are creating a Sibos prep SWAT team
    consisting of events, marketing, PR and technical participants --
    looking for several volunteers. Topics for which a strong technical
    point of view will be required include whether we can have a
    Hyperledger demo there, and if so, what and how?"
  - If you are interested in participating, please send a note to
    <a href="mailto:tbenzies@linuxfoundation.org" class="external-link"
    rel="nofollow"><span>tbenzies@linuxfoundation.org</span></a> and
    <a href="mailto:gwallace@linuxfoundation.org" class="external-link"
    rel="nofollow">gwallace@linuxfoundation.org</a>.

  

Virtual Hackathon Update (Dan Middleton)

- <a
  href="https://docs.google.com/document/d/1ROq44KpxuelkOp8GpceFNcv8K6XfWdaOnknzBk73OMc/edit"
  class="external-link" rel="nofollow"><span>On-going updates</span></a>

- Mic:  Are the virtual hackathons as effective as F2F?  Is this a model
  that we can use consistently?

- - Sheehan:  not as effective as F2F, but, if we explore some
    additional tools (with rooms full of people in different areas and
    used video conf, it could be).
  - Murali:  More than tools, the fact that we are in office makes it
    hard to take full part in hackathon (given other distractions)

- Suggestions for future virtual Hackathons

- - Regional "hubs" be set up to have groups around the world meet F2F
    in their respective locations to participate.
  - Run a virtual hackathon to include a weekend day such as Thursday
    thru Saturday vs. Wednesday thru Friday.
  - Lessons learned should be compiled at the closing of the current
    virtual Hackathon.

  

HIP identifier: Proposal to include
<a href="https://github.com/ghaskins/chaintool" class="external-link"
rel="nofollow"><span>chaintool</span></a> project repository in
hyperledger/fabric (Greg Haskins)

- <a
  href="https://docs.google.com/document/d/1CeUpHt9tHhwuQtBcmXMHBIQJ6XnkmU733zimvuyXkZo/edit"
  class="external-link"
  rel="nofollow"><span>https://docs.google.com/document/d/1CeUpHt9tHhwuQtBcmXMHBIQJ6XnkmU733zimvuyXkZo/edit</span></a>

- Discussion

- - Brian B:  Is this just a contribution to Fabric, or potentially a
    standalone underneath Hyperledger?

  - - Greg:  Came to it with fabric in mind; that said, with some
      refactoring it could be made more generic (it would take a little
      work).

  - Mic:  This is great.  I could imagine how this could be generalized
    -- concept of this tool would be useful regardless of underlying
    protocols.  One one hand, in favor of improving anything, but would
    like to see more generalized.

  - Greg:  Didn’t paint myself into a corner, this was just the initial
    place it fit nicely.

  - CF:  Would also like to see more generalized.  Who is willing to
    collaborate with Greg on this?

  - - Mic:  Can do some digging in.  In STL, we have transaction
      specification file (but it is really documentation).  In this you
      are taking abstraction, more than specification. What level can we
      start thinking about standards and interop.

  - CF:  is API based on swagger?

  - - Greg:  Not swagger, best described as protobuf (it tunnels through
      existing Fabric interface).  Merge between protobufs and existing
      fabric API.

  - Proposal to include
    <a href="https://github.com/ghaskins/chaintool" class="external-link"
    rel="nofollow"><span>chaintool</span></a> project repository in
    hyperledger/fabric

  - - VOTE:  Approved unanimously.  (Note: Emmanuel and Richard had
      dropped from the call by this time)
    - The TSC expressed interest to eventually rework this to function
      as a TLP.

  

**Action Items**

- ACTION:  Arnaud to take another pass on exit criteria and send to
  list.
- ACTION:  Brian to pull together first draft of release taxonomy in
  parallel to exit criteria
- ACTION:  Todd to finalize plan proposal for next several Hackathons: 
  July (west coast), August (virtual), September/October (EU) and
  distribute to list.

## Recording

* [https://youtu.be/v8GxOFppB_w](https://youtu.be/v8GxOFppB_w)
