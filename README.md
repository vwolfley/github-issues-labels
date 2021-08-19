# github-issues-labels
:label: A list of GitHub labels for reuse across projects.

## Use
:rocket: You can use the [git-labelmaker](https://github.com/himynameisdave/git-labelmaker) to import the labels to your project.

## How to organize product issues in Github
A approach to managing consistency across multiple repositories.

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
* `Mindless: documentation` - The issue or pull request relates to documentation.
* `Mindless: structure` -

#### Experience
Affect user’s comprehension, or overall enjoyment of the product. These can be both opportunities and “UX bugs”.
* `Experience: design` -
* `Experience: database` -
* `Experience: ux` -

#### Priority
Focused on describing the immediacy of attention required.
* `Priority: Critical` - The issue causes data loss, crashes or hangs processes, makes the system unresponsive, etc.
* `Priority: High` - The issue reports incorrect functionality, bad functionality, a confusing user experience, etc.
* `Priority: Medium` - The issue reports cosmetic items, formatting, spelling, colors, etc.
* `Priority: Low` - This issue can probably be picked up by anyone looking to contribute to the project, as an entry fix.

#### Status
Describes the decision state of the issue or pull request.
* `Status: blocked` -
* `Status: completed` -
* `Status: in-progress` -
* `Status: info-needed` - The issue needs more information before it can be verified and resolved.
* `Status: inactive` -
* `Status: on-hold` -
* `Status: review-needed` -
* `Status: wont-fix` - The issue is legitimate, but it is not something the team is currently able or willing to fix or implement.
* `Status: by-design` -
* `Status: cant-reproduce` - The issue is a bug and has been reviewed by a team member, but it cannot be replicated with the provided information and context. 
* `Status: <release>` - The issue is scheduled to be implemented by <Release>.
* 
#### Type
Describes the type of issue or pull request.
* `Type: bug` - The issue documents broken, incorrect, or confusing behavior. 
* `Type: discussion` -
* `Type: duplicate` - The issue is a duplicate of another feature request or bug report.
* `Type: enhancement` -
* `Type: feature` - The issue is a request for new functionality including changes, enhancements, refactors, etc.
* `Type: fix` -
* `Type: help-needed` -
* `Type: idea` -
* `Type: maintenance` -
* `Type: optimization` -
* `Type: testing` -

### Examples
* [Logical Github Labels](https://seantrane.com/posts/logical-colorful-github-labels-18230/)
* [Sane Github Labels](https://medium.com/@dave_lunny/sane-github-labels-c5d2e6004b63)
* [Robin Github Labels](https://robinpowered.com/blog/best-practice-system-for-organizing-and-tagging-github-issues)
* [Better Github Labels](https://blog.adam-marsden.co.uk/better-github-labels-f1360b43e0a7)
* [sensible-github-labels](https://github.com/Relequestual/sensible-github-labels)
* [SaltStack](https://docs.saltproject.io/en/latest/topics/development/labels.html)
