Ansible Role: Switch to Rocky Linux
=========

This role migrates CentOS to Rocky Linux with the official script provided by Rocky Linux.

Requirements
------------

None

Role Variables
--------------

See `defaults/main.yml` for a list of all variables.

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: fgierlinger.switch_to_rockylinux, tags: [migrate] }

License
-------

MIT

Author Information
------------------

Frédéric Gierlinger
