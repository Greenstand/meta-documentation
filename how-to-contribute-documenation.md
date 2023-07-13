---
description: Using Github and Gitbook
---

# How to Contribute Documenation

Greenstand documentation is maintained on Gitbook. It currently also exists in other places, but migration is underway.

## Introduction

Gitbook hierarchy is as follows:

`Organization` > `Collection` > `Space`

* Organization here is `Greenstand`. It holds all collections and spaces under it.
* Collection refers to a group of spaces. For example, the `Engineering` collection holds the Admin Panel, Web Map, etc. project spaces.
* Space refers to the documentation of a specific project, for example the Admin Panel. Each space is synced to a corresponding project repo on Github, in the `docs/` directory of the project repo.

A space can be published to the web for front-facing purpose, as accessing the Gitbook directly is on an invitation basis.&#x20;

The domain of the organization Gitbook is `greenstand.gitbook.io`, but it can also be accessed at `docs.greenstand.org`, which is more convenient.&#x20;

### Git Sync

Gitbook has a feature called Git Sync, which can sync bi-directionally with a Github repository. Meaning, commits to Github are synced to Gitbook, and edits to Gitbook become commits to Github. This allows us to maintain individual spaces without needing to consolidate the documentation in a single repo.

***

## Creating a new space

Creating a new space for a project on Gitbook is only possible for users with the necessary permissions. It cannot be done from Github. Please contact your team lead to obtain the permissions. You can still push the documentation onto Github, which can be synced to a new Gitbook space later.

Creating a space on Gitbook is straightforward. Once the new space is created:&#x20;

* Go to `Synchronize with Git` in the options menu.
* Click `Github` as provider, and connect to your Github account.

{% hint style="info" %}
You should have management permissions for the Github repo you want to sync to.
{% endhint %}

* Once authenticated, select the account, repository, and branch where you want to sync the space. (TODO branch, separate or main?)
* For `Monorepo`, it is highly recommended to store the documentation in a `docs/` directory (in the project root). Make sure to create one in the repo if not it isn't present.
* Choose `Fork Pull-Request Preview` as well.
* Finally, for `Choose Priority` :
  * If there is documentation already present in the Github repo, select Github to Gitbook.
  * If the documentation isn't alredy present in the Github repo, select Gitbook to Github.

***

### Contributing to existing documentation

If you want to contribute to the existing documentation of a project, you can do so in two ways:

* On Gitbook, if you have the necessary permissions
* On Github, using the Fork and Pull model, i.e, create a pull request for any documentation change.
  * If you are adding a new page, remember to update the `SUMMARY.md` with the page link, as Gitbook doesn't seem to update it automatically.
  * If you are creating a new document group, create a `README.md` as the main page of that group.
  * Assets (such as uploaded files, images, etc.) go in `.gitbook/assets`
