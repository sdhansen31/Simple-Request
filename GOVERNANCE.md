# <Project Name> Project Governance

*The Steering Committee should consume this template to create their own Governance document. Sections that require review are annotated with angle brackets (<>). The SC will also need to edit the README, CONTRIBUTOR, and COMMITTER templates as well. Make sure internal links between these four documents are correct.* 

## Steering Committee

This project is jointly governed by a Steering Committee (SC) which is responsible for high-level guidance of the project.

The SC has final authority over this project including:

*   Technical direction
*   Project governance and process (including this policy)
*   Contribution policy
*   Repository hosting
*   Release scheduling (subject to requests from Product Managers of products that consume this component)
*   Conduct guidelines
*   Maintaining the list of additional Committers
*   Maintaining the listing of this project in the [company-wide project listing](http://wiki.esecurity.net:8090/display/ENG/Internal+Open+Source#InternalOpenSource-ProjectCatalog).

Initial membership invitations to the SC may be given to individuals who are active contributors to this project, and who have significant experience with the management of the project. Membership is expected to evolve over time according to the needs of the project.

For the current list of SC members, see the project [README](README.md).

## Committers

The source repository is maintained by the SC and additional Committers who are added by the SC on an ongoing basis.

Individuals making significant and valuable contributions are made Committers and given commit-access to the project. These individuals are identified by the SC and their addition as Committers is discussed during the regular SC meeting.

**If you make a significant contribution and are not considered for commit-access, add a request to the next SC meeting as described in [SC_MEETINGS](SC_MEETINGS.md) or contact an SC member directly and it will be brought up in the next SC meeting.**

Modifications of the contents of the repository are made on a collaborative basis. Anybody with a source repository account may propose a modification via pull request and it will be considered by the project Committers; the requirements for such pull requests are documented in the [CONTRIBUTOR](CONTRIBUTOR.md) guide. All pull requests must be reviewed and accepted by a Committer with sufficient expertise who is able to take full responsibility for the change. In the case of pull requests proposed by an existing Committer, an additional Committer is required for sign-off. Consensus should be sought if additional Committers participate and there is disagreement around a particular modification. See _Consensus Seeking Process_ below for further detail on the consensus model used for governance.

Committers may opt to elevate significant or controversial modifications, or modifications that have not found consensus to the SC for discussion by sending a notification to all SC members and requesting a date by which the SC members will make a decision. The SC should serve as the final arbiter where required.

For the current list of Committers, see the project [README](README.md).

A guide for Committers is maintained in the [COMMITTER](COMMITTER.md) guide.

## SC Membership

SC seats are not time-limited. There is no fixed size of the SC. However, the expected target is between 6 and 12 to ensure adequate coverage of important areas of expertise, balanced with the ability to make decisions efficiently.

There is no specific set of requirements or qualifications for SC membership beyond these rules.

The SC may add additional members to the SC by a standard SC motion.

A SC member may be removed from the SC by voluntary resignation, or by a standard SC motion.

Changes to SC membership should be posted in the agenda, and may be suggested as any other agenda item (see "SC Meetings" below).

## SC Meetings

The SC meets at the time and location described in the file [SC_MEETINGS.md](SC_MEETINGS.md). The meeting is run by a designated moderator approved by the SC. Significant actions decided at each meeting should be published to [SC_MEETINGS.md](SC_MEETINGS.md).

Items are added to the SC agenda which are considered contentious or are modifications of governance, contribution policy, SC/Committer membership, or release process.

The intention of the agenda is not to approve or review all patches, that should happen continuously in the source repository and be handled by the larger group of Committers.

Any community member or contributor can ask that something be added to the next meeting's agenda by the process described in the file [SC_MEETINGS.md](SC_MEETINGS.md). Any Committer, SC member, or the moderator can add the item to the agenda by following the process described in [SC_MEETINGS.md](SC_MEETINGS.md).

Prior to each SC meeting the moderator will share the Agenda with members of the SC. SC members can add any items they like to the agenda at the beginning of each meeting. The moderator and the SC cannot veto or remove items.

The SC may invite persons or representatives from certain projects to participate in a non-voting capacity. These invitees currently are:

*   None

The moderator is responsible for summarizing the discussion of each agenda item and publishing the minutes to [SC_MEETINGS.md](SC_MEETINGS.md).

## Consensus Seeking Process

The SC follows a [Consensus Seeking](http://en.wikipedia.org/wiki/Consensus-seeking_decision-making) decision making model.

When an agenda item has appeared to reach a consensus the moderator will ask "Does anyone object?" as a final call for dissent from the consensus.

If an agenda item cannot reach a consensus a SC member can call for either a closing vote or a vote to table the issue to the next meeting. The call for a vote must be seconded by a majority of the SC or else the discussion will continue. Simple majority wins.