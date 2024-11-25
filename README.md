## git-lfs

[![CI](https://github.com/Oefenweb/ansible-git-lfs/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-git-lfs/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-git--lfs-blue.svg)](https://galaxy.ansible.com/Oefenweb/git_lfs)

Set up (the latest) [Git Large File Storage (LFS)](https://git-lfs.github.com/) in Debian-like systems.

#### Requirements

* `software-properties-common` (will be installed)
* `dirmngr` (will be installed)
* `apt-transport-https` (will be installed)
* `wget` (will be installed)
* `coreutils` (will be installed)

#### Variables

None

## Dependencies

None

## Recommended

* `ansible-latest-git` ([see](https://github.com/Oefenweb/ansible-latest-git))

#### Example

```yaml
---
- hosts: all
  roles:
    - oefenweb.git-lfs
```

#### License

MIT

#### Author Information

Mischa ter Smitten (based on work of [Pedro Carmona](https://github.com/pedrocarmona))

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-git-lfs/issues)!
