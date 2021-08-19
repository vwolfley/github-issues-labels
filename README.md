# github-issues-labels
:label: A list of GitHub labels for reuse across projects.

## Use
:rocket: You can use the [git-labelmaker](https://github.com/himynameisdave/git-labelmaker) to import the labels to your project.

## How to organize product issues in Github
A approach to managing consistency across multiple repositories.
These are descriptive labels which help to manage the list of issues.

### Label Groups
Mindless      | Experience | Priority | Status    | Type 
--------      | --------   | ------   | ------    | -- 
docs          | design     | low      | blocked   | bug
documentation | database   | medium   | completed | discussion
structure     | ux         | high     | in-progress | duplicate
|             |            | critical | inactive  | enhancement
|             |            |          | on-hold   | feature
|            |             |          | review-needed | fix
|            |             |          | wont-fix  | help-needed
|            |             |          | by-design | idea
|            |             |          | cant-reproduce | maintenance
|            |             |          |           | optimization
|            |             |          |           | testing

#### Mindless
Reorganizing folder structure, updating documents, documentation, and other necessary but less impactful tasks.
* `Mindless: docs` -
* `Mindless: documentation` - The issue or pull request relates to documentation of features or meta information, e.g. website, wiki, contribution guidelines, readme, etc.
* `Mindless: structure` -

#### Experience
Affect user’s comprehension, or overall enjoyment of the product. These can be both opportunities and “UX bugs”.
* `Experience: design` -
* `Experience: database` -
* `Experience: ui-ux` -

#### Priority
How important is this issue or task and what attention is required.
* `Priority: Critical` - The issue causes data loss, crashes or hangs processes, makes the system unresponsive, etc.
* `Priority: High` - The issue reports incorrect functionality, bad functionality, a confusing user experience, etc.
* `Priority: Medium` - The issue reports cosmetic items, formatting, spelling, colors, etc.
* `Priority: Low` - The issue would be a nice fix, but it mildly improves things that already work.

#### Status
Describes the decision state of the issue or pull request.
* `Status: blocked` - There is another issue that needs to be resolved first or some external blocker.
* `Status: completed` - Nothing further to be done with this issue. Awaiting to be closed by project member.
* `Status: in-progress` - This issue is actively being worked on, and has someone assigned.
* `Status: info-needed` - The issue needs more information before it can be verified and resolved.
* `Status: inactive` - It's believed that this issue is no longer important and no one else has shown an interest in it.
* `Status: on-hold` - The issue is accepted in principle, and is ready to be worked on, but will not be merged yet due to some interfering factor or condition.
* `Status: review-needed` - Should receive review by at least one other member in the team.
* `Status: wont-fix` - The issue is legitimate, but it is not something the team is currently able or willing to fix or implement.
* `Status: by-design` - The issue is a bug report of intended functionality.
* `Status: cant-reproduce` - The issue is a bug and has been reviewed by a team member, but it cannot be replicated with the provided information and context. 
* `Status: <release>` - The issue is scheduled to be implemented by <Release>.
* 
#### Type
Describes the type of issue or pull request.
* `Type: breaking` - The issue is a breaking change which requires a major version bump.
* `Type: bug` - The issue documents broken, incorrect, or confusing behavior. 
* `Type: discussion` - Further discussion or changes of confusing or incongruous behavior or documentation.
* `Type: duplicate` - The issue is a duplicate of another feature request or bug report.
* `Type: enhancement` - The issue is a new feature or a change to a feature which enhances the project.
* `Type: feature` - The issue is a request for new functionality including changes, enhancements, refactors, etc.
* `Type: fix` -
* `Type: help-needed` - The issue needs some help from team members.
* `Type: idea` -
* `Type: maintenance` - Updating phrasing or wording to make things clearer or removing ambiguity, without changing the functionality.
* `Type: optimization` -
* `Type: testing` - Adding missing tests or correcting existing tests.

### Examples
* [Logical Github Labels](https://seantrane.com/posts/logical-colorful-github-labels-18230/)
* [Sane Github Labels](https://medium.com/@dave_lunny/sane-github-labels-c5d2e6004b63)
* [Robin Github Labels](https://robinpowered.com/blog/best-practice-system-for-organizing-and-tagging-github-issues)
* [Better Github Labels](https://blog.adam-marsden.co.uk/better-github-labels-f1360b43e0a7)
* [sensible-github-labels](https://github.com/Relequestual/sensible-github-labels)
* [SaltStack](https://docs.saltproject.io/en/latest/topics/development/labels.html)
