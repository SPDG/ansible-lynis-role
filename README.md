Lynis
=========

Install and run `lynis`, to audit server.

Requirements
------------

Ubuntu box.

Role Variables
--------------

No variables at this stage.

Dependencies
------------

N/a.

Example Playbook
----------------

This will install lynis on servers:

    - hosts: servers
      roles:
         - { role: krecik.lynis }

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
