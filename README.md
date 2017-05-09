=========

base_python is a role to install python in the context of Ansible. It includes crypto extensions with compiled code.

Requirements
------------

RHEL-like, or Debian/Ubuntu system


Role Variables
--------------

'python_rhel' is a list of rpms available in your default yum repo.
'python_epel' is a list of rpms without RedHat support
'python_apts' is a list of packages for Debian/Ubuntu

Dependencies
------------

bbaassssiiee.base_epel is a role that this role depends on, see above.

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
