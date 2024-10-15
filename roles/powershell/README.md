pwsh
=========

Apply this role if you need to ensure the latest pwsh CLI is installed. 

Requirements
------------

- Access to internet. 
- Connection to Linux servers need sudo permission.
- Windows installations will leverage Chocolatey.
- Supported OSes
  - Debian
  - Fedora
  - RedHat
  - Windows

Role Variables
--------------

N/A

Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: servers
      roles:
         - pwsh

License
-------

BSD

Author Information
------------------

N/A
