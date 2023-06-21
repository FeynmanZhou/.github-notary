## Repositories

This document describes the lifecycle of repositories under the [Notary](https://github.com/notaryproject/).

Anyone can submit proposals regarding repositories' lifecycle by opening a GitHub issue in the
[notaryproject/.github](https://github.com/notaryproject/.github) repository. The [Notary governance maintainers](MAINTAINERS) will take into account the community feedback and decide on the proposal.

### Create a new sub-project

A new sub-project can be created as a repository and contributed to the Notary organization by opening a GitHub issue to request [Notary governance maintainers](MAINTAINERS) to vote in the
[notaryproject/.github](https://github.com/notaryproject/.github) repository. A new sub-project can be created after having a supermajority of approval from Notary governance maintainers.

If the decision is to add the proposed project, then one of the Notary GitHub organization admins will assist the issue opener in creating a repository or transferring an existing repository to the Notary organization. Upon creation, the repository must be reviewed to make sure it follows [Notary Governance](GOVERNANCE.md). 

### Lifecycle change 

A repository can be archived if the sub-project maintainers no longer maintain it or no activity for a long time. The sub-project maintainers of a given repository can propose changing its status by opening a GitHub issue in the [notaryproject/.github](https://github.com/notaryproject/.github) repository. The [Notary governance maintainers](MAINTAINERS) will take into account the community feedback and decide on the proposal.

#### Archiviation

Repositories showing little to no activity during the time span of a year can be proposed for Archiviation by opening a GitHub [issue](https://github.com/notaryproject/.github/issues). Once the proposal issue has a supermajority of approval from Notary governance maintainers, they can be archived. [Archived repositories](https://docs.github.com/en/repositories/archiving-a-github-repository/archiving-repositories) will remain inside the Notary GitHub organization but will be read-only and will not be maintained. As such, CODEOWNERS files contained in archived repositories are not valid.

In some cases, a repository is archived to reserve its name for future use.

#### Unarchiviation

Archived repositories can be proposed for unarchiviation by opening a GitHub issue in the [notaryproject/.github](https://github.com/notaryproject/.github) repository. Once the proposal issue has a supermajority of approval from Notary governance maintainers, the archived repository can be changed to active. In general, the same rules as for new repositories apply. 

### Removal

Repositories that show little relevance, are not maintained, or no longer have a purpose inside The Notary Project, can be proposed for removal by opening a GitHub issue in the [notaryproject/.github](https://github.com/notaryproject/.github) repository. Removed repositories will stop being maintained and will no longer be part of the Notary GitHub organization. In such a case, one of the Notary GitHub organization admins will assist the issue opener to delete the repository or transfer it to another place.

## Credits

Sections of this documents have been borrowed from [falcosecurity/evolution](https://github.com/falcosecurity/evolution/blob/main/REPOSITORIES.md).