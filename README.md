Oracle Java
=========

Install Oracle Java JDK

Requirements
------------
None


Role Variables
--------------
- `oracle_java_version`: (default: 8) Version of Oracle Java to install

Dependencies
------------
None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: munkyjunky.oracle-java, oracle_java_version: 8 }

License
-------
MIT
