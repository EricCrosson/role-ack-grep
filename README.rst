Ack-Grep
========

This role installs sensible ack defaults described by shuttlethread_.

.. _shuttlethread: http://shuttlethread.com/blog/useful-ack-defaults

Currently Supports
------------------

This role only currently supports :code:`apt` based systems (i.e. Ubuntu).

Example Playbook
----------------

Including an example of how to use your role (for instance, with
variables passed in as parameters) is always nice for users too::

    - hosts: servers
      roles:
         - { role: ack-grep }

License
-------

BSD
