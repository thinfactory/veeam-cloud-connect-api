# CONTRIBUTING.md

The following is a set of guidelines for contributing to this project; use your
best judgement and feel free to propose changes to this document in a pull
request.

Please take a moment to review this document in order to make the contribution
process easy and effective for everyone involved.

Following these guidelines show your respect to the time of the project owner
and developers managing and developing this project; in return, they will
reciprocate that respect by addressing your issue in a timely manner.

## Meet the Team

### Project Owner

The project owner is employed by the [THINFACTORY NV](https://GitHub.com/thinfactory)
organization and is responsible for:

* Creating and reviewing inbound requests such as questions, tasks, discussions, bug reports and feature requests
* Applying business values to the issues
* Guiding the dialogue between the project master and lead developer
* Prioritizing and planning issues to be handled in sprints
* Keeping track of the backlog
* Planning the roadmap and releases
* Managing the developers and provide feedback to contributors
* Resolving the issues assigned to him

Feel free to mention [@GeertHauwaerts](https://GitHub.com/GeertHauwaerts) if you
need any feedback from the project owner.

### Project Master

The project master is employed by the [THINFACTORY NV](https://GitHub.com/thinfactory)
organization and is responsible for:

* Reviewing the code quality and compliance with coding styles and standards
* Merging pull requests into the master branch and all feature branches
* Releasing new versions
* Guiding the dialogue between the project owner, lead developer and the devops team
* Translating business values into technical architectures and solutions
* Monitoring the continuous integration and intermediate builds

Feel free to mention [@GeertHauwaerts](https://GitHub.com/GeertHauwaerts) if you
need any feedback from the project master.

### Project Lead Developer

The project lead developers is employed or subcontracted by the
[THINFACTORY NV](https://GitHub.com/thinfactory) organization and is responsible
for:

* Collaborating with the project owner and master
* Participating in discussions, providing feedback and contributing his knowledge and experience
* Estimating the time effort required to handle an issue
* Guiding the dialogue between the project owner, developers and contributors
* Keeping track of the overall technical status of the project
* Guiding the daily review call between the project developers
* Joining the weekly review call with all stakeholders
* Resolving the issues assigned to him

Feel free to mention [@GeertHauwaerts](https://GitHub.com/GeertHauwaerts) if you need any
feedback from the project lead developer.

### Project Developers

The project developers are employed or subcontracted by the
[THINFACTORY NV](https://GitHub.com/thinfactory) organization and are
responsible for:

* Participating in discussions, providing feedback and contributing their knowledge and experience
* Joining the daily review call between the project lead developer, developers and contributors
* Joining the weekly review call with all stakeholders
* Resolving the issues assigned to them

### Project Contributors

The project contributors are individuals who are not part of the core
development team and are responsible for:

* Participating in discussions, providing feedback and contributing their knowledge and experience
* Joining the weekly review call with all stakeholders
* Submitting pull requests for their contribution

## Communication & Reviews

### Mentions

You can use the `@` and `#` symbols to notify and reference a user or team, or
to reference an issue in any comment or commit message.

More information about mentions is available on:

* [Mention Autocompletion](https://GitHub.com/blog/1004-mention-autocompletion)
* [Issues Features](https://guides.GitHub.com/features/issues)

### Check In Early, Check In Often

Developers who work for long periods, and by long we mean more than a day,
without checking anything into GitHub are setting themselves up for some serious
integration headaches down the line.

We much rather have small fragments checked in periodically than to go long
periods with no idea whatsoever what the developers and contributors are
writing.

As far as we are concerned, if the code isn't checked into GitHub, it doesn't
exist. If you learn to check in early and check in often, you'll have ample
time for feedback, integration, and review along the way.

> __Note:__
> All developers are required to commit their code at the end of the day,
> regardless of the state it's in.
 
### Markdown

Writing and commenting on issues is an art by itself, however, we strongly
encourage you to format your messages using markdown to optimize readability
and general communication.

More information on how to write and use markdown is available on:

* [Writing on GitHub](https://help.GitHub.com/articles/writing-on-GitHub)
* [GitHub Flavored Markdown](https://help.GitHub.com/articles/GitHub-flavored-markdown)
* [Markdown Basics](https://help.GitHub.com/articles/markdown-basics)
* [Mastering Markdown](https://guides.GitHub.com/features/mastering-markdown)

### Daily Review

The project is reviewed via teleconference every day at 9am, and is mandatory
to be attended by the project lead developer and the developers.

This call takes a maximum of 15 minutes and is intended to synchronize the
developers and provide an open dialogue to review:

* What did we do yesterday?
* Did we encounter any problems?
* What will we do today?
* Does anything need to be escalated?

### Weekly Review

The project is reviewed via teleconference every Monday morning between 9am and
11pm, and is mandatory to be attended by the project owner and the project
developers; all contributors are invited to participate in the call on a
voluntary base.

The following topics are discussed during the review:

* Review the previous sprint and their issues
* Schedule and review the issues to be handled in the next sprint
* Check the backlog and reprioritize if needed

## Project Workflow

Working on the project is easy; the following concepts outline the basic
life-cycle from an issue into a release.

* Issues are created by any stakeholder
* The project owner reviews all issues
* `discussion` issues collect information and become issues or `feature` issues
* Issues can be stand-alone, or be part of a `feature` issue, and may be tagged with a sprint milestone
* A `feature` issue is a collection of issues, and are tagged with a release milestone
* Developers work in issues with a sprint milestone
* Contributors work on issues with no sprint milestone
* Issues who are not referenced by a `feature` issue are pulled into the master branch
* Issues referenced by `feature` issue are pulled into a feature branch
* Feature branches are pulled into the master branch between the preceding release and the target release
* A release is a point in time where the completed issues features are declared as stable and production ready 

Don't start panicking just yet! All of the concepts outlined above are
explained in detail below :)

## Labels

We utilize several workflow labels to help organize and identify issues; here
is a list of the workflow labels used in this project and how we use them.

### Critical

Any issue tagged as `critical` is a high-priority request or a hotfix which
requires addressing with the highest priority.

> __Note:__
> This label is exclusively reserved for the project owner and master, any
> developer or contributor is explicitly forbidden to use this label.

### Discussion

Any issue tagged as `discussion` is an issue that requires general feedback and
is usually used in preparation for a feature issue.

After receiving the feedback from all stakeholders, we write the issue or issues
to address the problem or task to be performed by the developers and
contributors, and the discussion is closed.

The `discussion` label is only to be used on issues that have not yet been
screened.

### Feature

When we need a way to break down an issue in multiple smaller components, we
create an issue which is tagged as a `feature`.

In this feature issue, we create a list which contains all the individual
issues which are part of the feature. 

* [ ] #12 - Do something awesome
* [ ] #29 - Whow! Let's do something even more awesome
* [ ] #32 - ...

By using this method, we are able to keep track of issues which form part of a
larger scope.

> __Note:__
> This label is exclusively reserved for the project owner and master, any
> developer or contributor is explicitly forbidden to use this label.

### Task

Any issue tagged as `task` does not involve any code changes or development
efforts, and is used to keep track of operational matters or research.

For example, when we need to clean-up a database, investigate a new technology,
write a feature specification, or any other non-development task.

## Issues

### Project Owner & Master Issues

Issues submitted by the project owner or master should always be sufficiently
documented to allow any developer or contributor to handle the issue.

We encourage all developers and contributors to keep a watch for issues marked
as a `discussion` and provide their feedback at their own convenience.

### Developer & Contributor Issues

Issues submitted by developers and contributors will always be reviewed by the
project owner before any work is performed by the developers.

By screening and filtering our issues, we ensure that the developers and
contributors have all information they need prior to starting any work on the
issue.

If needed, the project owner will tag the issue as a `discussion` to request
feedback from the stakeholders, get a time estimate or other important
information.

After the project owner has reviewed the issue, the original issue is most
likely to be closed, and a new issue is created with contains the collective
information.

> __Note:__
> Developers will never handle issues which have not been reviewed by the
> project owner or master.

### Milestones

Issues that are part of a sprint are tagged with the corresponding sprint
milestone; if an issue is not tagged with any milestone, it is part of the
backlog.

If the issue is tagged as a `feature`, it will be marked with a release
milestone to indicate in which release the new feature is to be implemented.

As a general rule of thumb, non-feature issues will never be tagged with a
release milestone, and may be pulled into the master repository after
completion and review by the project master.

> __Note:__
> Applying or modifying a milestone is exclusively reserved to the project
> owner or master.

### Editing Issues

As a general rule of thumb, we do not allow to edit the content of an issue
after its review to prevent any unintentional changes in the scope of the issue.

The only exception to this rule is for the issues marked as a `feature`, which
are edited by the project owner to always display the updated status of the
request in a single view.

### Bug Reports

A bug is a _demonstrable problem_ that is caused by code in the project. Good
bug reports are extremely helpful, so thanks!

A good bug report shouldn't leave others needing to chase you up for more
information; please try to be as detailed as possible in your report:

* What is your environment?
* What steps will reproduce the issue?
* What browser(s) and OS experience the problem?
* Do other browsers show the bug differently?
* What would you expect to be the outcome?

All these details will help people to fix any potential bugs.

### Feature Requests

Feature requests are welcome, but take a moment to find out whether your idea
fits with the scope and aims of the project.

It's up to you to make a strong case to convince the project owner of the
merits of the feature; please provide as much details and context as possible.

## Branches

Branches are cool! They allow us to give our developers and contributors a
playground per issue or feature without impacting the master branch.

### Issue Branches

Any issue that is not tagged as a feature will have a branch named
`I_<number-of-issue>` which is used by the developers to handle the issue and
merge their changes into.

Issue branches are allowed to break builds and may contain code that is
considered as work-in-progress.

The lead developer is responsible for:

* Reviewing pull requests from contributors
* Merging pull requests into the issue branch

At the sole discretion of the lead developer, developers may be allowed to merge
their own requests into the issue branch.

When an issue is ready to be pulled into a feature branch or the master branch,
the lead developer will review the code, rebase the branch and issue an
upstream pull request.

> __Note:__
> When the issue branch is missing, you need to check whether the issue has
> been reviewed by the project owner.

> If the issue has been reviewed by the project owner, you need to mention
> the project master or lead developer who will create the issue branch.

### Feature Branches

Any issue tagged as a `feature` will have a branch named
`F_<number-of-feature-issue>` which is used by the project master to handle the
issues related to the feature.

Feature branches should always result in a working build and may only merge
completed code.

The project master is responsible for:

* Reviewing pull requests from the lead developer
* Merging pull requests into the feature branch

When a feature is ready to be pulled into the master branch, the project master
will perform a full review of the code, rebase the feature branch and issue a
pull request into the master branch.

> __Note:__
> When the feature branch is missing, you need to mention the project master or
> lead developer who will create the feature branch.

> It is explicitly forbidden for any developer to commit directly into the
> feature branch.

### Master Branch

This is the holy grail, the master branch contains the latest version of the
code and should always result in a working build.

The project master is responsible for:

* Reviewing pull requests for issues
* Merging pull requests into the master branch

> __Note:__
> It is explicitly forbidden for any developer to commit directly into the
> master branch.

### Human Readable Branches

At the sole discretion of the project master, branches might be appended with
two underscores, followed by a lower-case, human readable tag.

For example: 

* if we need a feature to implement awesome kittens, the project master might
name the branch `F_<number-of-feature-issue>__awesome_kittens`.
* if we need an issue branch to fix a broken leg, the project master might name
the branch `I_<number-of-issue>__fix_broken_leg`

As a general rule of thumb, human-readable named branches are only used for
issues where the duration to handle the issue exceeds 1 month.

## Pull Requests

Good pull request are a fantastic help and should remain focused in scope and
avoid containing unrelated commits.

Please ask first before embarking on any significant pull request such as
implementing features, refactoring code, porting to a different language,
otherwise you risk spending a lot of time working on something that the
project owner might not want to merge into the project.

Please adhere to the coding guidelines used throughout the project
(indentation, accurate comments, etc.) and any other requirements which may
apply.

You should not import vendor files and libraries into the repository, and use
tools such as bower, composer, npm instead. If possible the `.gitignore` file
should prevent said files from being imported.

Adhering to the following process is the best way to get your work included in
the project:

1. For contributors, [Fork](https://help.GitHub.com/fork-a-repo/) the project,
clone your fork, and configure the remotes:

   ```bash
   git clone https://GitHub.com/<your-username>/<project-name>.git
   cd <project-name>
   git remote add upstream https://GitHub.com/thinfactory/<project-name>.git
   ```

2. For developers, clone the project:

   ```bash
   git clone https://GitHub.com/thinfactory/<project-name>.git
   cd <project-name>
   ```

3. If you cloned a while ago, get the latest changes from upstream:

   ```bash
   git checkout master
   git pull upstream master
   ```

4. Go to the issue branch to write your feature, change, or fix:

   ```bash
   git checkout -b <branch-name>
   ```

5. Commit your changes in logical chunks. Please adhere to these
[git commit message guidelines](http://tbaggery.com/2008/04/19/a-note-about-git-commit-messages.html)
or your code is unlikely be merged into the project. Use Git's
[interactive rebase](https://help.GitHub.com/articles/interactive-rebase)
feature to tidy up your commits before making them public.

6. Locally merge (or rebase) the upstream development branch into the branch:

   ```bash
   git pull [--rebase] upstream master
   ```

7. Push your branch up to the remote repository:

   ```bash
   git push origin <branch-name>
   ```

8. [Open a Pull Request](https://help.GitHub.com/articles/using-pull-requests/)
with a clear title and description against the master or feature branch.

> __Disclaimer:__
> By submitting a patch, you agree to allow the [THINFACTORY NV](https://GitHub.com/thinfactory)
> organization to license your work under the terms of the project license. If
> no license is available, the license is considered to be closed-source and
> of proprietary nature.

## Code of Conduct

The [THINFACTORY NV](https://GitHub.com/thinfactory) organization strongly
values contributors from anywhere, regardless of gender, sexual orientation,
disability, physical appearance, body size, race, or religion.

As a result, the [THINFACTORY NV](https://GitHub.com/thinfactory) organization
has agreed to and enforces this code of conduct in order to provide a
harassment-free experience for everyone who participates in the development of
the project.

### Summary

Harassment in code and discussion or violation of physical boundaries is
completely unacceptable anywhere in the project, issue trackers, and other
components. Violators will be warned and then blocked or banned by the project
owner, master or lead developer at or before the 3rd violation.

### In Detail

Harassment includes offensive verbal comments related to gender, sexual
orientation, disability, physical appearance, body size, race, religion,
sexual images, deliberate intimidation, stalking, sustained disruption,
and unwelcome sexual attention.

Individuals asked to stop any harassing behavior are expected to comply
immediately.

Members of the [THINFACTORY NV](https://GitHub.com/thinfactory) organization,
including the project owner, master and developers, are also subject to the
anti-harassment policy.

If anyone engages in harassing behavior, including maintainers, we may take
appropriate action, up to and including warning the offender, deletion of
comments, removal from the project’s codebase and communication systems,
and escalation to GitHub support.

If you are being harassed, notice that someone else is being harassed, or have
any other concerns, please contact the project owner, master or lead developer
immediately.

Finally, don't forget that it is human to make mistakes! We all do. Let’s work
together to help each other, resolve issues, and learn from the mistakes that
we will all inevitably make from time to time.

### Thanks

Thanks to the [Bundler Code of Conduct](https://GitHub.com/bundler/bundler/blob/e3ce14f5ecd9b729338435c8689553ef209d83aa/CODE_OF_CONDUCT.md),
[JSConf Code of Conduct](http://jsconf.com/codeofconduct.html) and
[Fedora Code of Conduct](http://fedoraproject.org/code-of-conduct) for
inspiration and ideas.
