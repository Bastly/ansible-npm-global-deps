Role Name
=========

Install global dependencies from npm, like mocha for testing.

Requirements
------------

No specific requirements.

Role Variables
--------------

No vars needed.

Dependencies
------------

Depends on Nodejs

Example Playbook
----------------

requires sudo.

    - hosts: servers
      roles:
         - { role: ansible-npm-global-dependencies }

License
-------

AGPLv3

Author Information
------------------

Alejandro Vidal goofyahead@gmail.com - Gustavo Giudici gustavogiudici@gmail.com
