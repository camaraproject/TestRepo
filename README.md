<a href="https://github.com/camaraproject/TestRepo/commits/" title="Last Commit"><img src="https://img.shields.io/github/last-commit/camaraproject/TestRepo?style=plastic"></a>
<a href="https://github.com/camaraproject/TestRepo/issues" title="Open Issues"><img src="https://img.shields.io/github/issues/camaraproject/TestRepo?style=plastic"></a>
<a href="https://github.com/camaraproject/TestRepo/pulls" title="Open Pull Requests"><img src="https://img.shields.io/github/issues-pr/camaraproject/TestRepo?style=plastic"></a>
<a href="https://github.com/camaraproject/TestRepo/blob/main/LICENSE" title="License"><img src="https://img.shields.io/badge/License-Apache%202.0-green.svg?style=plastic"></a>
<a href="https://github.com/camaraproject/TestRepo/releases/latest" title="Latest Release"><img src="https://img.shields.io/github/release/camaraproject/TestRepo?style=plastic"></a>
<a href="https://github.com/camaraproject/Governance/blob/main/ProjectStructureAndRoles.md" title="Sandbox API Repository"><img src="https://img.shields.io/badge/Sandbox%20API%20Repository-yellow?style=plastic"></a>

# TestRepo

> [!WARNING]
> **This repository has been archived.** It was used for testing the [CAMARA release automation](https://github.com/camaraproject/tooling/tree/release-automation/release_automation) workflow ([tooling#72](https://github.com/camaraproject/tooling/issues/72)) during February 2026. It has been replaced by [`camaraproject/ReleaseTest`](https://github.com/camaraproject/ReleaseTest) for ongoing testing. Issues, releases, and branches in this repository are test artifacts only.

## Scope

Test repository for end-to-end validation of the automated release workflow. Contains a minimal API stub to exercise the full release lifecycle:

* Sync Release Issue from `release-plan.yaml`
* Create snapshot and release-review branch
* Generate CHANGELOG and README updates
* Publish release with branch protection enforced
* Post-release sync PR back to main

<!-- CAMARA:RELEASE-INFO:START -->
<!-- The following section is automatically maintained by the CAMARA project-administration tooling: https://github.com/camaraproject/project-administration -->

## Release Information

The repository has no (pre)releases yet, work in progress is within the main branch.

<!-- CAMARA:RELEASE-INFO:END -->

## Contributing

This repository is maintained by the CAMARA release management tooling team. It is not open for API contributions.
