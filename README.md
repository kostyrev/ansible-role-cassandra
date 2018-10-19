cassandra
=========

Ansible role to install Apache Cassandra.  
This role isn't supposed to configure Cassandra for it's done via Terraform later.

Dependencies
------------

Java should be already installed

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - { role: kostyrev.cassandra }

License
-------

BSD

Author Information
------------------

Aleksandr Kostyrev
