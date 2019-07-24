Consensus Enterprises' Matomo
=============================

Consensus Enterprises' Ansible role for provisioning Matomo (formerly known as "Piwik").

Requirements
------------

* A Debian-based OS (e.g. Ubuntu)
* The Nginx Web server
* MySQL (version 5.5 or greater) or MariaDB
* A DNS record pointing to the instance (e.g. `matomo.example.com`)

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

Testing
-------

Tests can be run like so (with more or less "v"s for verbosity):

```sh
ansible-playbook -vv --inventory TARGET_HOSTNAME, --extra-vars "VARIABLE1=VALUE1 VARIABLE2=VALUE2 ..." tests/TEST_NAME.yml
```

Feel free to add your own tests in `tests/`, using existing ones as examples.

Issue Tracking
--------------

For bugs, feature requests, etc., please visit the [issue tracker](https://gitlab.com/consensus.enterprises/ansible-roles/ansible-role-matomo/-/boards).

License
-------

GNU AGPLv3

Author Information
------------------

Written by Colan Schwartz and other folks at Consensus Enterprises.  To contact us, please use our Web form at https://consensus.enterprises/#contact .
