hdp-ranger-create-certs
=========

An ansible role to create self signed certificates to enable SSL communication
with the Ranger host and download them locally, so that they can be
distributed.

Requirements
------------


Role Variables
--------------


Dependencies
------------


Example Playbook
----------------


    - hosts: ranger
      roles:
         - { role: hdp-ranger-create-certs }

License
-------

BSD

Author Information
------------------

Stefan Kupstaitis-Dunkler (stefan.dun@gmail.com)
