# CLPR Governance

This document defines the initial governance rules of the [LFDT-CLPR](https://github.com/LFDT-CLPR) organization.
CLPR (Cross-Ledger Protocol) is a lab of the [LF Decentralized Trust](https://www.lfdecentralizedtrust.org) (LFDT).

All teams, their members, and the access rights of the teams on the repositories of the organization are defined in the [`teams.yml`](teams.yml) file.
Any change to a role or team is made by a pull request against this file.

Everyone who participates in CLPR must follow our [Code of Conduct](https://github.com/LFDT-CLPR/.github).

## Roles

### Contributors

Any person who contributes to CLPR is a Contributor.
A contribution can be anything from opening an issue, to writing code, to writing documentation, to reviewing pull requests or taking part in discussions.
We honor all legitimate contributions and want to make sure that they are recognized.
Contributors do not need any specific rights and are therefore not defined in a team.

A Contributor who shows consistent and valuable contributions over a reasonable period of time can be nominated by a Committer or Maintainer to become a Committer.

### Committers

Committers are defined **per repository**.
Each repository of the organization has its own committer team that is defined in [`teams.yml`](teams.yml).
The team follows the naming pattern `<repository-name>-committers` (for example `clpr-endpoint-committers` for the `clpr-endpoint` repository).
A person can be a Committer of multiple repositories.

A Committer has write access to the repository and can, for example, review and merge pull requests, assign issues, and create branches.

Committers are expected to:

- review pull requests to ensure they meet the standards of the project,
- actively contribute to the repository,
- help new contributors by creating and laddering issues,
- take part in project discussions on open channels and, if possible, in the weekly CLPR call.

We know that many people can only work on open source projects in their free time.
Their contributions are as valuable as those of people working full-time on the project.
Therefore, we do not define a minimum working time or response time for Committers.

### Maintainers

There is one maintainer team for the whole organization: **`clpr-maintainers`**.

The Maintainers are the group that takes general decisions for the organization.
This includes, among others:

- creating new repositories,
- adding (and removing) Committers,
- adding (and removing) Maintainers,
- any other decision that affects the organization as a whole.

Next to that, Maintainers see themselves as stewards of CLPR.
It is the responsibility of the Maintainers to shape CLPR into a place that is as diverse and community-friendly as possible.
Maintainers should actively encourage a diverse contributor and maintainer community and avoid an unnecessary concentration of project governance within a single organization.
Appointments should always be based on demonstrated contribution, trust, and the needs of the project.
Maintainers must ensure a welcoming environment for all developers and community members.

All responsibilities described for Committers apply to Maintainers as well.

## General teams

Next to the committer teams and the maintainer team, the organization has the following general teams.
They exist to enable configuration, security, and administration of the organization.

- **`clpr-release-engineers`**: Members of this team are responsible for the release configuration of the repositories, including CI/CD pipelines and release processes.
- **`security-maintainers`**: Members of this team are responsible for the security of the repositories, including security tooling, automated scanners, and the handling of reported vulnerabilities.
- **`lfdt-staff`**: This team contains staff members of the LF Decentralized Trust that need (mostly administrative) rights on the organization.
  The members of this team are managed by the LFDT.

## Decision making

### Consensus first

Decisions should ideally be made by consensus.
Only if no consensus can be reached, or if a formal decision is required (for example to add a new Committer or Maintainer), a vote of the Maintainers is held.

### Issues

Every decision of the Maintainers should be tracked by an issue in this repository.
The issue describes the proposal and is used to document the discussion and the result of the decision.

For the creation of a new repository, an issue in this repository is **mandatory**.
The issue should contain the name and the purpose of the new repository as well as the initial Committers.

Changes to teams or members are additionally done by a pull request against [`teams.yml`](teams.yml) that references the corresponding issue.
The pull request is merged once the decision has been made.
Please use the matching pull request template (for example "Create New Repository" or "Vote Required") as described in the [README](README.md#creating-prs-in-the-governance-repository).

### Voting

Votes can be held in two ways:

- **Synchronous voting in the weekly CLPR call**: A vote can be held in the [weekly CLPR call](https://zoom-lfx.platform.linuxfoundation.org/meetings/lf-decentralized-trust-labs?view=week&occurrence=1793023200) if more than 50% of all Maintainers are present.
  The result of the vote is documented in the corresponding issue.
- **Asynchronous voting**: If the quorum is not reached in the call, or if a vote should not wait for the next call, the vote is held asynchronously in the corresponding issue or pull request.
  An asynchronous vote runs for **14 days**.
  The creator of the vote should notify all Maintainers that a vote is open.

A vote passes when more Maintainers have voted in favor (+1) than against (-1).
Maintainers who abstain or do not vote are not counted.
For example, 2 votes in favor and 0 against with 10 abstentions is a passing vote.

A vote can be closed early when the outcome can no longer change based on the remaining votes.
For example, if a majority of all Maintainers has already voted in favor, the vote passes regardless of how the remaining Maintainers vote.
Conversely, if so many Maintainers have voted against that the remaining votes can no longer produce more +1 than -1, the vote fails early.

Maintainers who vote against a proposal should give the reason in the issue or pull request.

## Changing the governance

These rules are the initial governance of CLPR.
Changes to this document are proposed by a pull request and follow the decision-making process described above.
