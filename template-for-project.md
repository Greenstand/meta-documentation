---
description: Guidelines for documentation template
---

# Template for project

_"People don't read, they scan"_

The two primary places where a user encounters Greenstand documentation are Github and Gitbook. There may be other auxiliary sources such as Google Docs, but we deal with only the first two here.

In general, it is more helpful to use shorter paragraphs, more images, and code blocks wherever appropriate. The less monotonous the documentation reads, the more engaged a user will be.

{% hint style="info" %}
**NOTE**

The following guidelines are more suited to technical projects, i.e, the Engineering teams, than the Operations teams.
{% endhint %}

## Gitbook

This template is with respect to a project space. Some sections may or may not apply to your project. Others may be added at your discretion.

* Overview
  * Functionalities
  * Dependencies
* Getting started/ Quickstart&#x20;
  * Link to `README.md`
  * Troubleshooting
* Connect
  * Team members, roles
  * Slack channel&#x20;
  * Team meeting schedule (+ link to Google calendar)
* Design and Architecture

## Github

This template is with respect to a project repo.

For all projects, there must be `README.md` , `CONTRIBUTING.md`  ,`LICENSE.md` , and `CODE_OF_CONDUCT.md` files. A `CHANGELOG.md` file may also be applicable depending on the project.

#### README.md

The `README` is the first thing a user sees when entering the repository. Its purpose is to provide a concise and informative description of the project, along with instructions for setting up and running the project.&#x20;

It should contain links to other important documents, such as the contributing guidelines, advanced documentation (Gitbook), relevant projects, etc.

The following sections must be present in the `README.md` of a project:

* Badges (slack, etc.) (shields.io)
* Description
* Table of contents (optional)
* Tech stack
* Getting started
  * Setting up environment
  * Install and run the project
* Testing
* Troubleshooting (link to Gitbook Troubleshooting page)
* Link to Gitbook project space
* Contributing Guidelines
  * Working on an issue, reporting a bug, suggest new feature, donating, or getting help.&#x20;
  * Link to `CONTRIBUTING.md`
* License (link to `LICENSE.md)`
* Code of Conduct (link to `CODE_OF_CONDUCT.md`)

#### CONTRIBUTING.md

This file contains the contribution guidelines for the project.

* Welcome note
* Table of contents
* Code of conduct (link to `CODE_OF_CONDUCT.md`)
* Getting an issue assigned
* Working on an issue
* Commit message and PR title format
* Keeping your fork in sync
* Bug reporting
* Suggest new feature
* Code style guide
* Where to get help (email, slack)
* Donation

#### LICENSE.md

See [https://github.com/Greenstand/Greenstand-Overview/blob/master/License%2C%20Code%20of%20Conduct%20etc/LICENSE](https://github.com/Greenstand/Greenstand-Overview/blob/master/License%2C%20Code%20of%20Conduct%20etc/LICENSE)

#### CODE\_OF\_CONDUCT.md

See [https://github.com/Greenstand/Greenstand-Overview/blob/master/License%2C%20Code%20of%20Conduct%20etc/CODE\_OF\_CONDUCT.md](https://github.com/Greenstand/Greenstand-Overview/blob/master/License%2C%20Code%20of%20Conduct%20etc/CODE\_OF\_CONDUCT.md)

## References

* [https://contributing.md/how-to-build-contributing-md/](https://contributing.md/how-to-build-contributing-md/)
* [https://dev.to/merlos/how-to-write-a-good-readme-bog](https://dev.to/merlos/how-to-write-a-good-readme-bog)
