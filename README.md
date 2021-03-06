Ansible Xen Orchestra
=========

Ansible role for building Xen Orchestra (https://xen-orchestra.com) on FreeBSD and Linux systems.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

None for the xen-orchestra role, however, you will need a Redis server available and some HTTP frontend server is advised for proxying traffic and SSL termination (Nginx, Apache, etc.).

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: bartekrutkowski.xen-orchestra }

License
-------

BSD

Author Information
------------------

Bartlomiej Rutkowski <contact at robakdesign dot com>
