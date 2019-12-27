connman
=========

Installs and configures connman-vpn on a Debian 10 system.

Requirements
------------

None.

Role Variables
--------------

| Variable Name | Default Value | Description |
--------------- |---------------|--------------
`connman_vpn_providers` | [] | optional, VPNs to configure

Dependencies
------------

My [connman role](https://github.com/ThreeFx/connman) or a working connman installation.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables
passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: connman, x: 42 }

License
-------

BSD

Author Information
------------------

Find me on [GitHub](https://github.com/ThreeFx).
