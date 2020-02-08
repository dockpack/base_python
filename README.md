[![Galaxy](https://img.shields.io/badge/galaxy-dockpack.base__python-blue.svg?style=flat)](https://galaxy.ansible.com/dockpack/base_python)
![Build Status](https://api.travis-ci.com/dockpack/base_python.svg)

base_python
=========

base_python is an ansible-role to install python in the context of Ansible.
It includes crypto extensions with compiled code.

Requirements
------------

For testing you need Docker.
For running you need RHEL-like, or Debian/Ubuntu system


Role Variables
--------------

```
- Software collections offer latest versions of programming languages
`collections_enabled: true`

- approved/test release of software collections' python
`python_collection: rh-python36`


'python_rhel' is a list of rpms available in your default yum repo.
'python_epel' is a list of rpms without RedHat support
'python_apts' is a list of packages for Debian/Ubuntu
```

Dependencies
------------

You need access to EPEL for some RPMs. This is a weak dependency.
dockpack.base_epel is a role that you can use for this.

https://www.softwarecollections.org/en/docs/


Example Usage
----------------

Refer to a complete build server https://github.com/bbaassssiiee/buildserver

License
-------

MIT

Author Information
------------------

Bas Meijer
@bbaassssiiee
