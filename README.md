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
structure     | ux         | high     | duplicate | enhancement
|             |            | critical | in progress | feature
|            |             |          | inactive  | fix
|            |             |          | on-hold   | help needed
|            |             |          | review needed | idea
|            |             |          | wont-fix   | maintenance
|            |             |          | by-design  | optimization
|            |             |          | cant-reproduce | testing

#### Mindless
Reorganizing folder structure, updating documents, documentation, and other necessary but less impactful tasks.

#### Experience
Affect user’s comprehension, or overall enjoyment of the product. These can be both opportunities and “UX bugs”.

#### Priority
Focused on describing the immediacy of attention required.
* **Priority: Critical** - This should be dealt with ASAP. Not fixing this issue would be a serious error.
* **Priority: High** - After critical issues are fixed, these should be dealt with before any further issues.
* **Priority: Medium** - This issue may be useful, and needs some attention.
* **Priority: Low** - This issue can probably be picked up by anyone looking to contribute to the project, as an entry fix.

#### Status
Describes the decision state of the issue or pull request.

#### Type
Describes the type of issue or pull request.

### Examples
* [Logical Github Labels](https://seantrane.com/posts/logical-colorful-github-labels-18230/)
* [Sane Github Labels](https://medium.com/@dave_lunny/sane-github-labels-c5d2e6004b63)
* [Robin Github Labels](https://robinpowered.com/blog/best-practice-system-for-organizing-and-tagging-github-issues)
* [Better Github Labels](https://blog.adam-marsden.co.uk/better-github-labels-f1360b43e0a7)
* [sensible-github-labels](https://github.com/Relequestual/sensible-github-labels)
* [SaltStack](https://docs.saltproject.io/en/latest/topics/development/labels.html)
