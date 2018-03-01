![Build Status](https://api.travis-ci.org/dockpack/base_python.svg)

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
'python_rhel' is a list of rpms available in your default yum repo.
'python_epel' is a list of rpms without RedHat support
'python_apts' is a list of packages for Debian/Ubuntu
```

Dependencies
------------

You need access to RPMs from EPEL. This is a weak dependency.
dockpack.base_epel is a role that you can use for this.

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
