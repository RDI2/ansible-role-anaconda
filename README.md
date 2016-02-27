Ansible Role - anaconda
=======================

This role installs [Anaconda](https://www.continuum.io/downloads).

Platforms
---------

CentOS 6.7 is the only platform that is supported and tested so far.

Role Variables
--------------

- Check out [defaults/main.yml](defaults/main.yml)

Dependencies
------------

None.

Download Role
-------------

For examples:

```bash
ansible-galaxy install RDI2.anaconda
ansible-galaxy install -p roles/ RDI2.anaconda
```

Also, if you have ansible role file, you can add this role like this:

```bash
- src: RDI2.anaconda
```

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: RDI2.anaconda }

License
-------

MIT License.

Author Information
------------------

- Koji Tanaka, RDI2
