Ansible role: Certbot
=========

Deploys TLS certificates signed by Letsencrypt using Certbot.

Verification is done with Amazon's Route53 DNS service.

Requirements
------------

The domain requested in the certificate must be managed in Amazon's Route 53 service and you must be able to provide a set of access keys with privileges to add TXT records to Route 53 for domain verification.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

This role has no dependencies.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-certbot }

License
-------

GNU GPLv3
