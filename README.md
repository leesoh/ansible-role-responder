Responder
=========

Ansible Galaxy role for Python Responder.

Requirements
------------

None

Role Variables
--------------

responder_git_location: '/opt'

Dependencies
------------

leesoh.git

Example Playbook
----------------

Responder it up:

    - hosts: servers
      roles:
         - { role: leesoh.responder }

License
-------

BSD

Author Information
------------------
Python Responder: https://github.com/lgandx/Responder
