# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.3.0](https://github.com/lotusnoir/ansible-system_repo_epel/compare/0.2.0...0.3.0) - 2025-11-26

### Commits

- update main to include success flag at the end to be able to monitor last playbook run [`73088c3`](https://github.com/lotusnoir/ansible-system_repo_epel/commit/73088c3679b928acc847293912d69984e6bfa9f2)

## [0.2.0](https://github.com/lotusnoir/ansible-system_repo_epel/compare/0.1.0...0.2.0) - 2025-11-18

### Commits

- update core and molecule [`f03c4d0`](https://github.com/lotusnoir/ansible-system_repo_epel/commit/f03c4d0296a5313f2e7d8ec9c051c3bdbceb05c1)
- add oraclelinux10 support + lint and core fixes [`f43549b`](https://github.com/lotusnoir/ansible-system_repo_epel/commit/f43549be1f2a14e239688c8ac4f56c2b1ee64f85)

## 0.1.0 - 2025-10-29

### Merged

- Remove spaces around repo file "enabled" option [`#55`](https://github.com/lotusnoir/ansible-system_repo_epel/pull/55)
- Various testing improvements [`#54`](https://github.com/lotusnoir/ansible-system_repo_epel/pull/54)
- Use the "epel_repo_disable" value to toggle whether epel is enabled or not [`#51`](https://github.com/lotusnoir/ansible-system_repo_epel/pull/51)
- Use URL to retrieve the repo gpgkey [`#45`](https://github.com/lotusnoir/ansible-system_repo_epel/pull/45)
- add ability to disable epel repo after install [`#41`](https://github.com/lotusnoir/ansible-system_repo_epel/pull/41)
- fixed result check syntax [`#31`](https://github.com/lotusnoir/ansible-system_repo_epel/pull/31)
- updated yaml syntax, use : instead of = [`#33`](https://github.com/lotusnoir/ansible-system_repo_epel/pull/33)
- Fix #23 [`#25`](https://github.com/lotusnoir/ansible-system_repo_epel/pull/25)
- Don't error GPG import in check mode [`#18`](https://github.com/lotusnoir/ansible-system_repo_epel/pull/18)
- Don't install repo if it is already installed [`#17`](https://github.com/lotusnoir/ansible-system_repo_epel/pull/17)
- Fix for issue #8 - more reliable installation. [`#14`](https://github.com/lotusnoir/ansible-system_repo_epel/pull/14)
- PR #13: Use current official URL for epel_repo_url. [`#13`](https://github.com/lotusnoir/ansible-system_repo_epel/pull/13)
- Use static url links, fixes #9. [`#10`](https://github.com/lotusnoir/ansible-system_repo_epel/pull/10)
- Update RHEL 7.0 EPEL version to current version [`#7`](https://github.com/lotusnoir/ansible-system_repo_epel/pull/7)
- Update to newest epel-release for EL7. [`#3`](https://github.com/lotusnoir/ansible-system_repo_epel/pull/3)
- Make role work on EL 4, 5 and 7. [`#1`](https://github.com/lotusnoir/ansible-system_repo_epel/pull/1)

### Fixed

- Use URL to retrieve the repo gpgkey [`#43`](https://github.com/lotusnoir/ansible-system_repo_epel/issues/43)
- Fixes #42: Import GPG key for EPEL before installing the repo. [`#42`](https://github.com/lotusnoir/ansible-system_repo_epel/issues/42)
- Merge pull request #25 from trinitronx/fix-spurious-already-installed-failure [`#23`](https://github.com/lotusnoir/ansible-system_repo_epel/issues/23)
- Fix #23 [`#23`](https://github.com/lotusnoir/ansible-system_repo_epel/issues/23)
- Fixes #20: Bump minimum Ansible version requirement for ansible_check_mode use. [`#20`](https://github.com/lotusnoir/ansible-system_repo_epel/issues/20)
- Merge pull request #10 from rahulsundaram/fixurl [`#9`](https://github.com/lotusnoir/ansible-system_repo_epel/issues/9)
- Use static url links.  resolves #9 [`#9`](https://github.com/lotusnoir/ansible-system_repo_epel/issues/9)

### Commits

- add trixie (debian13) support [`ac116d6`](https://github.com/lotusnoir/ansible-system_repo_epel/commit/ac116d649bfd170ff3a7018552392c4e2e8deec1)
- update core, molecule + gitlab-ci [`5b0357d`](https://github.com/lotusnoir/ansible-system_repo_epel/commit/5b0357d0533d2ee6e6eca19102cc8b3e74dc56d3)
- initial commit [`f6ba3fd`](https://github.com/lotusnoir/ansible-system_repo_epel/commit/f6ba3fd858fecb58316d3df3090ff8f857449c4a)
- Initial commit [`bb00339`](https://github.com/lotusnoir/ansible-system_repo_epel/commit/bb00339401784e1b15ab51884e1f40f0c8cef998)
- initial commit [`89af68e`](https://github.com/lotusnoir/ansible-system_repo_epel/commit/89af68e3746293732b29dbaee57f08d545ec4ecb)
- Make local dev with molecule a little easier. [`85a896b`](https://github.com/lotusnoir/ansible-system_repo_epel/commit/85a896b225b55d797f21e892449fc4595d71bc2d)
- Stale bot is now Stale GitHub Action. [`5fd89af`](https://github.com/lotusnoir/ansible-system_repo_epel/commit/5fd89af2f157c82ac1d6f4a48dcdd352878a2114)
- Remove official support for RHEL. Rocky/Alma/Stream support is best-effort. [`f8bd6cb`](https://github.com/lotusnoir/ansible-system_repo_epel/commit/f8bd6cb5738d27bab0b4bfdfd85e613af90884e1)
- Fix Molecule CI workflow since docker plugin has moved. [`96f98fd`](https://github.com/lotusnoir/ansible-system_repo_epel/commit/96f98fd456f0988d0886fe7b2cdc3b50e3a455bf)
- Fix Molecule CI workflow for Ubuntu 22.04 GitHub Actions. [`0233d3f`](https://github.com/lotusnoir/ansible-system_repo_epel/commit/0233d3f2bc022ba33d99515d86748b4c087985be)
