# Documentation Framework

### Project Scope

The scope of this documentation project includes:

* Indexing and auditing the status of all existing documentation
* Bringing the documentation into a standardized and editable format and following the DPG standard opensource best practices
* Removing old and irrelevant documentation
* Updating and standardizing all project-critical documentation

### Activities

* [ ] Recruit and Appoint Documentation Project Lead and Project Manager
  * Appointment of a Project Lead and Project Manager
* [x] [Complete inventory of existing documentation](documentation-framework.md#indexing-existing-documentation)&#x20;
  * MD file on Github with links and descriptions of all documentation
* [ ] [Perform an audit of Greenstand’s existing information and documentation. Include what exists now, where it's located, updates needed, and any gaps, and enhancement opportunities.](documentation-framework.md#auditing-existing-information)
  * Adding document status to the MD file on Github with links and descriptions of all documentation.
* [ ] [Research options and best practices for Documentation structure](documentation-framework.md#standardizing-the-documentation)
  * Create a publicly accessible and linked road map file outlining path forward for documentation.
* [ ] [Identify and articulate needs/wants/desires for each of Greenstand’s three core audiences.](documentation-framework.md#greenstand-core-audiences)
  * MD file on Github containing research findings, outlining the current project state and suggestions for how to move forward
* [ ] Identify problem areas and outline the current process for onboarding core audiences.
  * MD file on Github with links to relevant onboarding files, recommended enhancements, additions/deletions, and processes for making updates ongoing
* [ ] Create a roadmap, and identify tasks, milestones, risks, the full scope, and key players required for the implementation of the documentation project.
  * Publicly viable road map with open tickets and tickets assigned to individual contributors.
* [ ] Project Management "project board set up
  * Using the audit findings to create tickets, log dependencies, and assign tasks.
* [ ] Identify opportunities to drive audience engagement with interactive or multi-media formats
  * Md file on Github with recommendations for videos or advanced Slack programming. Note: The creation of videos may occur as a second phase of the initiative.
* [ ] Detailed review, rewriting, and revisions of documentation to enable volunteers of all skill levels to advance their skills here.
  * Advanced well-written documentation for all stakeholders with a focus on easy-to-find-and-follow pathways for volunteer contributors of all levels.
* [ ] [Create a centralized documentation portal. Consolidation, indexing, and advancement of all critical documentation issues discovered in the audit.](documentation-framework.md#consolidating-documentation)
  * A single well organized portal at `docs.greenstand.org`
* [ ] [Document and communicate a process for accessing, and maintaining/updating documents in the portal. Create supporting documentation. Develop oversight requirements and a process for updating/maintaining the portal.](documentation-framework.md#support-documentation)
  * Clear documentation.
* [ ] Communicate as necessary to raise awareness of the new portal and explain the process for document migration.
  * Migrated documents.
* [ ] [Consolidate/migrate documentation, including archiving documentation and repositories that are old, outdated, or obsolete.](documentation-framework.md#archiving-old-documentation)
  * Clear and accurate documentation.

### Gitbook vs Github Pages

Gitbook is far more convenient to use than Github Pages.&#x20;

The latter requires managing the individual project deployments, in addition to learning Jekyll + Just The Docs format. Updating the theme also requires manually updating each project, which is trivial but undoubtedly tedious.

Hosting all documentation on only Github restricts contribution and editing of the documentation using Markdown and pull requests, which may be inconvenient to non-technical contributors. Gitbook can be synced with Github, which allows for contribution from the Github side if desired.

Gitbook also provides more sophisticated access management, and integrations with third party services like Figma, Slack, etc.&#x20;

In conclusion, although Github Pages may work with some initial effort, Gitbook provides solutions for most of the current issues with documentation.

### Indexing existing documentation

* See [Documentation Inventory](documentation-inventory.md) for the list of all currently existing documentation.

### Auditing existing information

The documentation is outdated, ambiguous, partial, and scattered. It exists in sources such as:

* In various Gitbook spaces, many of which are inaccesible as:
  * their published spaces are not linked anywhere
  * their published spaces are not indexed by google
  * the Greenstand Gitbook is locked behind authorization
* In repos and wikis as given in the [Documentation Inventory](documentation-inventory.md)

### Standardizing the documentation

<figure><img src=".gitbook/assets/img.png" alt=""><figcaption><p>Types of Documentation</p></figcaption></figure>

Using the above image as a guideline, we can divide the documentation into 2 types (for now):

1. User Documentation (End users)
2. Technical/System Documentation (Contributors)
   * We ignore the third party integrations for later

*   **User documentation**

    * Support Portals
    * FAQs
    * Video tutorials
    * Step-by-step guides
    * Embedded assistance
    * Software requirements.
    * Installation guide.
    * How to start the system.
    * How to use features of a product.
    * Screenshots explaining those features.
    * Contacts of the developer if an undocumented question arises and more.

    > Source: [https://medium.com/@kesiparker/technical-documentation-vs-user-documentation-ff68e7de1985](https://medium.com/@kesiparker/technical-documentation-vs-user-documentation-ff68e7de1985)
* **Technical documentation**
  * How the review process works
  * Style guides
  * Schedules
  * Design and Implementation
  * Release process checklists
  * Tools to use for development
  * How to use the build process
  * Coding practices to follow
  * Process to release a build to QA for testing
  * Deploy or release a product
  * May use jargon or industry-specific terms

#### New framework

* All documentation is up to date
* Keeping a changelog
* Sustainable processes for maintaining documentation.
* Organizing spaces in proper collections hierarchy
  * Publishing collections instead of individual spaces is an option
  * Customization to make each collection look distinct?&#x20;

### Greenstand Core Audiences

1. Growers
2. Organizations
3. Contributors

### Consolidating documentation

* Single Documentation Portal
* All the documentation is consolidated under `docs.greenstand.org`, via Gitbook
* All relevant project repos have a `docs/` directory corresponding to a Gitbook space.

### Support documentation

### Archiving old documentation

### TODOs

* Standardize documentation for project repos
  * README.md
    * Summary
    * Installation steps
    * Contributing guidelines
    * Link to Github space
  * Gitbook space
  * No wikis

