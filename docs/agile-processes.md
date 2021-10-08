## Product Backlog

The product backlog consists of all of the issues that are not in the current sprint. It is the product owner's responsibility to priorize items in the backlog, to ensure that all requirements are gathered and expressed in each issue and to define the definition of done for each issue.

### Grooming

Issues are discussed and prepared for planning, where a quorum will size the issues. Issues can be prioritized by the product manager by assigning them to future sprints. As more and more issues are sized and as the team gets better at sizing, it will become easier to determine the product roadmap and when features will be complete.

## Sprints

### Backlog

The sprint backlog should consist of sized issues that the team commits to doing within the sprint duration. This backlog is pulled from the product backlog in accordance to the product manager's priority and the goal or theme of the sprint.

### Duration

This can vary from team to team and should be agreed upon by the whole team. If the sprints are too short, the team will struggle to meet their commitments. If they're too long the release cadence may not be sufficient to meet stakeholder agreements.

### Lanes

Lanes are useful to track the progress of an issue. At the minimum, there should be four lanes:
1. Current Sprint – This lane initially holds all of the issues for a sprint and consists of issues that are not started or have been returned in the workflow.
2. In Progress – Consists of issues that are assigned and in development. A developer should limit the number of items in this lane to only items they're actually working on.
3. In Review – Issues that have completed development and are ready for review. A PR template should be used to help the developer prepare the PR and the reviewers understand what they are reviewing.
4. In QA – Issues that have passed peer review live here. Notes should be prepared to help those who will perform QA understand what and how they're testing it.

Once an issue passes QA, it will be closed.

#### Pulling in new issues
- If there are no more issues to pickup and assistance cannot be provided to others, then a sized issue may be pulled from the product backlog.
- Priorities can change mid-sprint and if a new issue must be pulled in, then an issue of equal size should be taken out.

### Planning

Planning occurs before the start of a sprint. Items that are in the product backlog are sized by the team and assigned to a sprint. With a properly groomed backlog, the team may not need much time, as the issues may already be sized and assigned to the sprint. The team should decide on the total number of story points and add or remove issues until they arrive at or close to that number. Any remaining questions should be answered during this time. Sprint planning should not involve design discussions so if long disucssions occur, it's likely the item is not ready for the sprint and should be moved to the product backlog.

By the end of planning the team should agree to what is in the sprint. If there is still time remaining, the team should continue to size issues in the product backlog.

### Retrospective

The team should review and discuss their performance on the last sprint. Good questions to ask during this time are:
1. Were all items in the sprint complete?
2. Was the theme or goal of the sprint met?
3. Were issues over estimated? Why?
4. Were issues under estimated? Why?
5. What went well with the sprint?
6. What didn't go well?

It's important that the team can have an open conversation and learn from their mistakes. Most of the time, it isn't any one person's fault why an issue took longer than expected.

### Sizing or Story Point Estimation

This is one of the most difficult aspects of the job and should be taken seriously. It is also a team effort, since everyone brings a different perspective. If an issue requires QA, then it should be represented in the story point.

Story points are a unit of measure used to express the overall effort required to fully implement an issue in the backlog. Factors involved are:
- work complexity
- amount of work
- risk or uncertainty

Story points should be used to understand the size and prioritization of work and are **not** a measure of productivity.

Points differ from hours, but it is often useful to have a baseline to start the team off with. As time goes on, these points will have different meanings to different teams. The more the team can break up an issue, the more accurate their estimations should be. In general, teams should avoid bringing issues into the sprint that cannot be completed within that same sprint.

**Only to form a starting baseline, if teams are unfamiliar with story point estimation**
- 1 point - 1-2 hours
- 2 points - 4 hours
- 3 points - 1 day
- 5 points - 2 to 3 days
- 8 points - 1 week
- 13 points - 2 weeks


### Standups

Standups should occur every day or as many days as possible. The three main questions that should be answered are:
1. What did you do yesterday?
2. What are you doing today?
3. Do you have any blockers?

Each developer should answer these questions and any conversations that may come out of them should generally be side-tabled, though this can be hard to do.
