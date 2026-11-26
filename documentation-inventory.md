# Documentation Inventory

## Current inventory — 26 November 2026

The signed-in Greenstand GitBook inventory contains **45 spaces**. This is an inventory of visible spaces, not certification that every page is current. Space modification dates do not establish the accuracy of their content.

Use [Greenstand documentation](https://docs.greenstand.org) for public reading and [GitBook](https://app.gitbook.com/) for editing. Confirm effective space permissions and the actual Git Sync configuration before assuming a repository edit will publish. The Admin Panel site showed Git Sync disconnected during this review.

### Review status

| Area                | Evidence and next action                                                                                                                                                                                                     |
| ------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Admin Panel         | Obsolete meeting section removed through change request #101; Sebastian reports it published. Architecture and permissions pages still need reconciliation with the open implementation PRs.                                 |
| Engineer’s Handbook | PR #205 merged on 26 November 2026: https://github.com/Greenstand/Greenstand-Overview/pull/205. The current GitBook Handbook reflects the updated software-role wording and removal of obsolete meeting guidance.            |
| Mobile App          | Reviewed mobile content is saved in Mobile App change request #39, including the dated 8-million capture count and offline routing proposal context. Awaiting review and publication. Source documentation PR #90 is merged. |
| System Design       | Public navigation includes a localhost overview link; correction prepared in the documentation source. Deployment status must be checked separately from architecture proposals.                                             |
| Other spaces        | Inventoried below. Content and ownership review remains outstanding; age alone is not a reason to rewrite policies or delete historical records.                                                                             |

### Spaces observed

| Collection                      | Spaces                                                                                                                                                                                                                |
| ------------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Common / Engineering            | Engineer’s Handbook; ReactJS Guidelines                                                                                                                                                                               |
| Common                          | System Design; Onboarding; Meta-Documentation                                                                                                                                                                         |
| Engineering / Admin Panel       | Admin Panel; Freetown; drafts                                                                                                                                                                                         |
| Engineering / Web Map           | Web Map; Impact Map; Tile Server                                                                                                                                                                                      |
| Engineering / Wallet Admin      | Overview; Development; End User                                                                                                                                                                                       |
| Engineering / Treetracker       | Mobile App; GIZ                                                                                                                                                                                                       |
| Engineering / Infrastructure    | Onboarding cloud engineering; Application Platform; Kubernetes; Keycloak; aws; User and Auth System; PostgreSQL exporter on prometheus                                                                                |
| Engineering / APIs and services | Greenstand Microservices; Treetracker API; Microservices Product Documentation                                                                                                                                        |
| Engineering                     | Machine Learning; Automation; Agile Programing; Data Flow                                                                                                                                                             |
| Experimental Teams              | Programs; Freetown; Botany; Blockchain                                                                                                                                                                                |
| Operations                      | Communications Policies & Procedures v2; Design; HubSpot Email Workflow; Communications Lead Training Manual; Treetracker Liaison Workspace; Fundraising Case Statement; Grants; Human Resources; Operations Handbook |
| Standalone                      | Wallet; Serverless/FAAS                                                                                                                                                                                               |

Duplicate names such as Freetown and Overview refer to different spaces. Collection labels above group the observed inventory for readability. Do not merge or delete them solely because their names overlap.

### Sources for current technical work

* [Admin client PR #1315](https://github.com/Greenstand/treetracker-admin-client/pull/1315) and [Admin API PR #699](https://github.com/Greenstand/treetracker-admin-api/pull/699): open integration work, not evidence of production deployment.
* [Decision proposal #35](https://github.com/Greenstand/treetracker-decisions/pull/35): stakeholder membership, project-based session ownership and offline Android implications; proposed, not accepted policy.
* [Android issue #1468](https://github.com/Greenstand/treetracker-android/issues/1468): App Links work; distinguish it from authorization and session allocation.

Recurring team-meeting schedules are no longer current, as confirmed by Sebastian. Remove attendance directions from active guidance; preserve historical minutes.

## Historical inventory — July 2023

The following is retained as a historical reference. Its publication, synchronization and deletion recommendations have **not** been revalidated and must not be treated as current configuration.

The grant-application/documentation plan calls for "indexing and auditing the status of all existing documentation." To that end, here is a list of directories, repos, websites, etc. that contain documention, as of July 14, 2023.

This list includes all the documents listed in issue 18 of the greenstand-documentation repo ([https://github.com/Greenstand/greenstand-documentation/issues/18](https://github.com/Greenstand/greenstand-documentation/issues/18))

Let's expand, amend, and annotate this list to keep track of document status: Is a file up-to-date? Rewritten as an \*.md file in this repo? Deleted?

### Status

* **Up to date** - nothing needs to be done
* **To be reviewed** - quality of information needs to be determined
* **To be updated** - information may be outdated, ambiguous, or missing
* **To be deleted** - irrelevant, unnecessary or redundant
* **Unknown**

### This Repo

* [https://github.com/Greenstand/greenstand-documentation/tree/main](https://github.com/Greenstand/greenstand-documentation/tree/main)

### Other Repos

* [https://github.com/Greenstand/Greenstand-Overview/tree/main](https://github.com/Greenstand/Greenstand-Overview/tree/main)
* [https://github.com/Greenstand/treetracker-decisions/tree/main](https://github.com/Greenstand/treetracker-decisions/tree/main)
* [https://github.com/Greenstand/treetracker-infrastructure-adr/tree/main](https://github.com/Greenstand/treetracker-infrastructure-adr/tree/main)

### `greenstand.org` Website

* [https://greenstand.org/devbox](https://greenstand.org/devbox)
* [https://greenstand.org/docs](https://greenstand.org/docs)
  * To be deleted (redundant, present in `greenstand-documentation`)
* [https://greenstand.org/documentation](https://greenstand.org/documentation)
  * To be deleted ( redundant, present in `greenstand-documentation`)

### Wikis

* [https://github.com/Greenstand/Greenstand-Overview/wiki](https://github.com/Greenstand/Greenstand-Overview/wiki)
* [https://github.com/Greenstand/treetracker-android/wiki](https://github.com/Greenstand/treetracker-android/wiki)
* [https://github.com/Greenstand/treetracker-ios/wiki](https://github.com/Greenstand/treetracker-ios/wiki)
* [https://github.com/Greenstand/treetracker-gis/wiki](https://github.com/Greenstand/treetracker-gis/wiki)
* [https://github.com/Greenstand/treetracker-web-map-api/wiki](https://github.com/Greenstand/treetracker-web-map-api/wiki)
* [https://github.com/Greenstand/treetracker-infrastructure/wiki](https://github.com/Greenstand/treetracker-infrastructure/wiki)
* [https://github.com/Greenstand/treetracker-admin-api/wiki](https://github.com/Greenstand/treetracker-admin-api/wiki)

### Gitbook

* [https://app.gitbook.com/@greenstand](https://app.gitbook.com/@greenstand)
* Overview
  * [https://docs.greenstand.org/auth-system](https://docs.greenstand.org/auth-system)
  * Synced with [https://github.com/Greenstand/greenstand.github.io/tree/main](https://github.com/Greenstand/greenstand.github.io/tree/main)
* GIZ
  * [https://docs.greenstand.org/giz](https://docs.greenstand.org/giz)
  * Published as unlisted url, not indexed by search engines
* Onboarding
  * [https://docs.greenstand.org/onboarding](https://docs.greenstand.org/onboarding)
* Freetown
  * Historical restricted Freetown space; access through the organization inventory.
* Drafts
  * [https://docs.greenstand.org/drafts](https://docs.greenstand.org/drafts)
* Engineering
  * Engineer's Handbook
    * [https://docs.greenstand.org/engineering/](https://docs.greenstand.org/engineering/)
    * Synced with [https://github.com/Greenstand/Greenstand-Overview/tree/gitbook-sync](https://github.com/Greenstand/Greenstand-Overview/tree/gitbook-sync)
  * Web Map
    * [https://docs.greenstand.org/web-map/](https://docs.greenstand.org/web-map/)
    * Unknown if synced to any Github repo
  * ReactJS Working Group
    * [https://docs.greenstand.org/reactjs-working-group](https://docs.greenstand.org/reactjs-working-group)
  * Application Platform
    * [https://docs.greenstand.org/application-platform](https://docs.greenstand.org/application-platform)
    * Unknown if synced to any Github repo
  * Machine Learning
    * [https://docs.greenstand.org/machine-learning](https://docs.greenstand.org/machine-learning)
    * Unknown if synced to any Github repo
  * Impact Map
    * [https://docs.greenstand.org/impact-map](https://docs.greenstand.org/impact-map)
  * Data Reporting
    * [https://docs.greenstand.org/data-reporting](https://docs.greenstand.org/data-reporting)
  * Admin Panel
    * [https://docs.greenstand.org/admin-panel](https://docs.greenstand.org/admin-panel)
  * Mobile App
    * [https://docs.greenstand.org/mobile-app](https://docs.greenstand.org/mobile-app)
  * Microservices Working Group
    * [https://docs.greenstand.org/microservices-working-group/](https://docs.greenstand.org/microservices-working-group/)
    * Synced with [https://github.com/Greenstand/microservices-documentation/tree/main](https://github.com/Greenstand/microservices-documentation/tree/main)
  * Treetracker API / Mapnik Server
    * [https://app.gitbook.com/o/-MXNadx4i6aOZ12XcStA/s/UnWPz1580gx1f3eSDEc1/](https://app.gitbook.com/o/-MXNadx4i6aOZ12XcStA/s/UnWPz1580gx1f3eSDEc1/)
    * Currently unpublished (as a part of Engineering collection)
  * User and Auth System
    * [https://docs.greenstand.org/auth-system/](https://docs.greenstand.org/auth-system/)
  * Wallet Admin Client
    * [https://docs.greenstand.org/wallet-admin-client/](https://docs.greenstand.org/wallet-admin-client/)
  * System Design
    * [https://docs.greenstand.org/system-design](https://docs.greenstand.org/system-design)
    * Synced with [https://github.com/Greenstand/system-design-docs/tree/master](https://github.com/Greenstand/system-design-docs/tree/master)
* Experimental Teams
  * Botany
    * [https://docs.greenstand.org/botany](https://docs.greenstand.org/botany)
    * Unknown if synced to any Github repo
  * Blockchain
    * [https://docs.greenstand.org/blockchain/](https://docs.greenstand.org/blockchain/)
* Operations
  * Operations Handbook
    * [https://docs.greenstand.org/operations-handbook/](https://docs.greenstand.org/operations-handbook/)
    * Published as unlisted url, not indexed by search engines
  * Fundraising Case Statement
    * [https://docs.greenstand.org/operations/](https://docs.greenstand.org/operations/)
    * Published as part of Operations collection
  * Human Resources
    * [https://docs.greenstand.org/operations/v/human-resources/](https://docs.greenstand.org/operations/v/human-resources/)
    * Published as part of Operations collection
    * Unknown if synced to any Github repo
  * Treetracker Liaison Checklists
    * [https://docs.greenstand.org/operations/v/treetracker-liaison-workspace/](https://docs.greenstand.org/operations/v/treetracker-liaison-workspace/)
    * Published as part of Operations collection
  * Communications Policies and Procedures v2
    * [https://docs.greenstand.org/operations/v/communications-policies-and-procedures-v2/](https://docs.greenstand.org/operations/v/communications-policies-and-procedures-v2/)
    * Published as part of Operations collection
    * Unknown if synced to any Github repo
  * Communications Lead Training Manual
    * [https://docs.greenstand.org/operations/v/communications-lead-training-manual/](https://docs.greenstand.org/operations/v/communications-lead-training-manual/)
    * Published as part of Operations collection
    * Unknown if synced to any Github repo
  * Grants
    * [https://docs.greenstand.org/operations/v/grants/](https://docs.greenstand.org/operations/v/grants/)
    * Published as part of Operations collection
    * Unknown if synced to any Github repo
  * HubSpot Email Workflow
    * [https://docs.greenstand.org/operations/v/untitled-1/](https://docs.greenstand.org/operations/v/untitled-1/)
    * Published as part of Operations collection
    * Unknown if synced to any Github repo
  * Design
    * [https://app.gitbook.com/o/-MXNadx4i6aOZ12XcStA/s/mMqp4Nu2K1a93bf6oSUN/](https://app.gitbook.com/o/-MXNadx4i6aOZ12XcStA/s/mMqp4Nu2K1a93bf6oSUN/)
    * Currently unpublished
    * Unknown if synced to any Github repo
* Programs
  * Programs
    * [https://docs.greenstand.org/programs/](https://docs.greenstand.org/programs/)
  * Wallet Operator
    * [https://app.gitbook.com/o/-MXNadx4i6aOZ12XcStA/s/-Ma06v9oiMS8sdJdbT3J/](https://app.gitbook.com/o/-MXNadx4i6aOZ12XcStA/s/-Ma06v9oiMS8sdJdbT3J/)
    * Currently unpublished
  * Data Flow
    * [https://docs.greenstand.org/data-flow/](https://docs.greenstand.org/data-flow/)
  * Freetown
    * [https://docs.greenstand.org/freetown-statistics/](https://docs.greenstand.org/freetown-statistics/)
    * Published as unlisted url, not indexed by search engines
* Documentation
  * Automation
    * [https://docs.greenstand.org/automation/](https://docs.greenstand.org/automation/)
    * Published as unlisted url, not indexed by search engines
  * Meta-Documentation
    * [https://docs.greenstand.org/meta-documentation/](https://docs.greenstand.org/meta-documentation/)
    * Synced with [https://github.com/Greenstand/meta-documentation/tree/main](https://github.com/Greenstand/meta-documentation/tree/main)
  * Microservices Documentation
    * [https://docs.greenstand.org/microservices-documentation/](https://docs.greenstand.org/microservices-documentation/)
