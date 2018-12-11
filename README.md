Role Name
=========

A role to install a docker swarm.

Requirements
------------

Docker must be installed to use this role.

Role Variables
--------------

TODO
A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

tiflor.ansible_docker installs the required dependencies docker.

Example Playbook
----------------

Quite simple example. Instead of using the group vars to define the necessary global vars, the can be defined in the play.

    - hosts: servers
      roles:
        - ansible-dockerswarm

License
-------

MIT

Author Information
------------------

DevOps Engineer, some of my work can be found on [gitub](https://github.com/tiflor)
