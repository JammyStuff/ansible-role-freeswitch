freeswitch
==========

Ansible role to install and configure the FreeSWITCH Software Defined Telecom stack.

Requirements
------------

The following requirements need to be met by the node executing the role:

- gpg (gnupg package)

Role Variables
--------------

### freeswitch_release

Sets the release of FreeSWITCH to install. Possible values are 1.4, 1.6, or 1.8. Defaults to 1.8.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - role: jammystuff.freeswitch

License
-------

MPL 2.0

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
