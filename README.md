stack-common
=========

This role is used by ENA for items that are "common" across all ENA stacks.  For example, we want to ensure that curl is
installed on all stacks, so we added a task that ensures that it will be installed.

Requirements
------------

Reguires sudo


Role Variables
--------------

There are currently no variables for this role.

Dependencies
------------

There are currently no external role dependencies for this role.

Example requirements.yml file
-----------------------------
```yaml
- src: git+http://stack-utility.ena.net/role/common.git
  name: ena-common
```

Example Playbook
----------------
```yaml
- hosts: all
  roles:
    - ena-common
```

License
-------

Apache License 2.0

Author Information
------------------

Education Networks of America
