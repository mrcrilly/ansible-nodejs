Role Name
=========

Installs Node.js and NPM for RHEL 6. It uses the EPEL repo, which is installed for you if it's not found (epel.repo isn't present)

Requirements
------------

Make sure you have '/etc/yum.repos.d/epel.repo' in place or let the role install it for you.

Role Variables
--------------

None

Dependencies
------------

- EPEL repository, but this is managed for you

Example Playbook
----------------

    - hosts: servers
      roles:
         - mrcrilly.nodejs

License
-------

BSD

Author Information
------------------

- Michael Crilly
- http://mrcrilly.me/
- @mrcrilly
