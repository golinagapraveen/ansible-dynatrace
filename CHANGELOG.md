# Changelog

All notable changes to this project will be documented in this file.

## [1.1.0] - 2021-10-06

- Fixed malformation of `--restart-service` parameter, passed to `oneagentctl`.
- Fixed problem with installation for higher versions of Ansible.
- Improved `oneagentctl` configuration mechanism.

## [1.0.0] - 2021-08-13

- Added capability of creating download directory structure during deployment.
- Added `oneagent_validate_certs` parameter.
- Added capability of cleaning up downloaded artifacts in case of deployment's failure.

## [0.4.0] - 2021-06-25

- Removed `oneagent_remove_signature` parameter.
- Added ability to configure installation using `oneagentctl`.
- Removed the need to provide the required parameters in case of uninstallation.
- Added node restart option. 

## [0.3.0] - 2021-02-12

- Fixed role's idempotence.

## [0.2.1] - 2020-12-28

- Fixed minor problems with example playbooks and inventory files.

## [0.2.0] - 2020-11-18

- Added new parameter `oneagent_platform_install_args` allowing to specify platform-specific installer arguments.
- Changed `oneagent_local_installer` parameter to pass only single path to local installer.

## [0.1.0] - 2020-09-25

- Initial [Preview](https://www.dynatrace.com/support/help/shortlink/preview-and-early-adopter-releases) release.
