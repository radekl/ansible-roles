Role Name
=========

SSH server configuration

Requirements
------------

- Currently only Debian 8 (and derivatives)

Role Variables
--------------

By default role will create single ssh daemon (with default configuration)

For advanced usages, user may specify more than one daemon configuration (it will create another daemon instance which 
will use different config file)

Dependencies
------------

(null)

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: ssh.servers
      roles:
         - role: ssh

License
-------

(null)

Author Information
------------------

Radek L.
