# Project Governance
This document outlines our project management, team coordination, and decision-making processes at Lodger.

For guidance on how to contribute to Lodger, please see our [contribution guidelines](https://github.com/lodgerapp/.github/blob/main/CONTRIBUTING.md). For our code conduct, please see our [code of conduct](https://github.com/lodgerapp/.github/blob/main/CODE_OF_CONDUCT.md).

## Project Roles

-   **Contributor**: A contributor is anyone who aids in enhancing the quality of the project's codebase, documentation, or marketing.

-   **Collaborator**: A collaborator is a reliable contributor, selected by the Lodger team, to aid in refining a particular feature or aspect of the project. This individual is typically an "external collaborator" with triage/write access to the repository.

-   **Maintainer**: A maintainer is a steady collaborator trusted by the Lodger team, demonstrating a capacity for ownership of a specific area within Lodger.

-   **Lead Maintainer**: The lead maintainer directs and oversees the execution of ideas for a distinct area in Lodger. This person defines the direction, implements strategies, and even recruits maintainers or collaborators to assist in reaching the defined goal.

## Collective Responsibility
Regardless of the individual role, every collaborator and maintainer share three fundamental attributes:

1. They share accountability for the project's success.
2. They have made a long-term, recurring time investment to improve the project.
3. They are dedicated to accomplishing necessary tasks, even if they are not the most engaging or enjoyable.

Maintainers are often under-appreciated as their work is usually behind the scenes. It's effortless to appreciate an advanced, technically impressive feature. Yet, appreciating the absence of bugs, gradual improvement in stability, or the reliability of a release process can be more challenging. However, these aspects are what differentiate a good project from a great one.

## How we make decisions

### On recruting new members
**Contributor >> Collaborator >> Maintainer (Team member)**

Maintainers, primarily, are contributors who have demonstrated a long-term commitment to the success of a project. Those aspiring to be maintainers are anticipated to actively contribute to the codebase, documentation, pull request reviews, and issue triage in the project for over three months.

However, mere contributions do not suffice for becoming a maintainer. It's essential to earn the trust of the project's current maintainers, proving oneself to be reliable and capable of making decisions in the project's best interest.

The existing maintainers periodically compile a list of contributors who have consistently engaged with the project in the preceding months. From this list, potential maintainer candidates are identified and proposed in the `#maintainers` channel on Discord.

After a candidate is informally introduced in the #maintainers channel, the current maintainers are invited to share their thoughts, raise any concerns, and express their support. Subsequently, [@wibb36](https://github.com/wibb36) will set up a call to formally invite the proposed individual to the team.

### On adding new features / projects

For collaborators and contributors, every new feature idea or request starts out
with a Pull Request describing:

-   The scope of the feature
-   The problem it solves
-   The proposed solution and API
-   The proposed list of contributors who will manage the bug fixes, documentation, and support
-   Any additional information that'll be useful for the Lodger maintainers to understand the scope and nature of the project.

If a project is approved, a core maintainer will guide and work closely with the author to bring the idea to life.

Community projects are solely maintained by the community and not maintained by the core team.

## Teams

**Core**: They're responsible for the overall quality and stewardship of the project. They are people who understand a specific area of Lodger deeply enough to improve, make changes and improve performance of the project.

**Funding**: They're actively involved in getting funding and sponsorship opportunities for the project. Being a startup with low-budget can leave the impression that you're working for free. While this is the reality, we strive hard to ensure
that everyone is compensated for the work they do. No matter how little!

**Design**: They're responsible for creating the design system and ui components used in Lodger and documentation websites for the project. They also help create marketing graphics, youtube thumbnails, etc. as needed.

**Experiments**: They're always working on the "next big thing", trying out new approaches to existing problems or inventing novel solutions to long-standing industry problems.

## Projects
Here's a list of project currently ongoing in the Lodger organization:

| Repository         | Responsibility                                              | Leads              |
| ------------------ | ----------------------------------------------------------- | ------------------ |
| lodger.app        | Build and maintain the front-end web app/platoform | [@wibb36](https://github.com/wibb36)            |
| lodger-servers    | Build and maintain the back-end and middleware              | [@wibb36](https://github.com/wibb36)            |
| project management | manage Lodger projects on GitHub                           | [@wibb36](https://github.com/wibb36) |
| Docs               | Improve docs and translate to other languages               | [@wibb36](https://github.com/wibb36)            |
| Content            | Create content, posts and videos                            | [@wibb36](https://github.com/wibb36)|

## Team management policies

### Stepping down
Life priorities, interests, and passions can change. If you're a maintainer but
feel you must remove yourself from the project, inform other maintainers that
you intend to step down, and if possible, help find someone to pick up your
work. At the very least, ensure your work can be continued where you left off.

After you've informed other maintainers, create a pull request to remove
yourself from the `MAINTAINERS.md` file and add yourself to the
`HALL_OF_MAINTAINERS.md`

### Removal of inactive maintainers
Similar to the procedure for adding new maintainers, existing maintainers can be
removed from the team if they don't show significant activity on the project
within 6-8 months.

If a maintainer has shown insufficient activity over this period, a neutral
person will contact the maintainer to ask if they want to continue being a
maintainer. If the maintainer decides to step down as a maintainer, they open a
pull request to be removed from the `MAINTAINERS.md` file.

If an inactive maintainer didn't have the time to open their own pull request,
another maintainer may open up the pull request.

## Common questions

### I'm a maintainer. Should I make pull requests too?
Yes. Pushing directly to the main branch must never occur. All alterations should invariably be implemented through a pull request.

### How do we manage conflicts?
If you have a technical dispute that you feel has reached an dead-end with a
subset of the community, any contributor may open an issue, specifically
recommended an actionable step forward.

### Do we have meetings?
Yes, we meet every Thursday (6PM GMT-7) to discuss status updates and share ideas.