# CLPR Technical Governance

[![License](https://img.shields.io/badge/license-apache2-blue.svg)](LICENSE)

This repository contains all governance documents of the CLPR project:

- The `config.yaml` file that is used to configure all GitHub repositories of the organization.
  https://clowarden.io is used as tool to manage the GitHub resources and the change list for all Hiero repos can be found [here](https://clowarden.io/audit/?organization=LFDT-CLPR).

## Creating PRs in the Governance Repository

There are five templates available for creating PRs. The best way to choose between them is with URL switching.

| Template Name            | URL Switch                                                                                                            | Description                                          |
|--------------------------|-----------------------------------------------------------------------------------------------------------------------|------------------------------------------------------|
| Organization Default     | `https://github.com/LFDT-CLPR/governance/compare/main...<my-branch>?quick_pull=1`                                     | Default template for PRs                             |
| Custom Properties Update | `https://github.com/LFDT-CLPR/governance/compare/main...<my-branch>?template=custom_properties_update_pr_template.md` | Use when modifying custom properties file            |
| Create New Repository    | `https://github.com/LFDT-CLPR/governance/compare/main...<my-branch>?template=new_repository_pr_template.md`           | Use when creating a new repository                   |
| Create New Team          | `https://github.com/LFDT-CLPR/governance/compare/main...<my-branch>?template=new_team_pr_template.md`                 | Use when creating a new team                         |
| Vote Required            | `https://github.com/LFDT-CLPR/governance/compare/main...<my-branch>?template=vote_pr_template.md`                     | Use when adding new members or changing member roles |

## Getting Started

- For a comprehensive and detailed overview of CLPR, please refer to the technical documentation and related resources available at https://github.com/LFDT-CLPR.

## Contribute

- To contribute, please refer to the [CLPR's contribution guidelines](https://github.com/LFDT-CLPR/.github/blob/main/CONTRIBUTING.md).

## License

- CLPR's source code is available under the **Apache License, Version 2.0 (Apache-2.0)**[Apache License 2.0](LICENSE.md).
