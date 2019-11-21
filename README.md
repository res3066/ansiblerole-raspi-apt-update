raspi-apt-update
=========

Runs apt-get update && apt-get upgrade on a raspberry pi.

Generally a reasonable prerequisite for doing other configuration, since if you have a stale apt cache you may find that software you wish to install is no longer available.

Requirements
------------

none

Role Variables
--------------

none - will be some in the next iteration or three

for your requirements.yml:

- src: https://github.com/res3066/ansiblerole-raspi-apt-update
  name: raspi-apt-update
  scm: git


Dependencies
------------

none

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - raspi-apt-update

License
-------

MIT

Author Information
------------------

Rob Seastrom <rs@seastrom.com>

