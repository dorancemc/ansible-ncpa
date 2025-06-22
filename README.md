dorance.ansible-ncpa
====================

Role to install and configure ncpa client

Requirements
------------

None

Role Variables
--------------

Variables definition can be found in the defaults/main folder

Dependencies
------------

None

Example Playbook
----------------

Include this role in your playbook on this way:

```yaml
- hosts: servers
  roles:
    - { role: dorancemc.ansible-ncpa, tags: [ ncpa ] }
```

You can get detail results of ncpa from logs:
```bash
tail -f /usr/local/ncpa/var/log/ncpa_*
```

License
-------

Apache-2.0

Author Information
------------------

Dorance Martinez @dorancemc
