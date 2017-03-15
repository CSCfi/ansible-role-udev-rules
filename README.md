ansible-role-udev-rules
=========

Configure udev rules

Currently this role can only template in a "smart array max_sectors_kb" override for block devices.

Ideally it should not have any rules by default but users should be able to new ones by just defining some variables.

https://github.com/CSC-IT-Center-for-Science/ansible-role-udev-rules/issues/3

Requirements
------------


Role Variables
--------------

<pre>
udev_smart_array_max_sectors: True
</pre>

Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-udev-rules }

License
-------

MIT

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
