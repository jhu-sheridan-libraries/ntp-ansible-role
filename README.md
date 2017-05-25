ntp-ansible-role
=========

A role to install and setup a simple ntp client using ntpdate

Requirements
------------

None

Role Variables
--------------

"ntpservers":[]
    This should be a list of ntp servers that will populate ntp.conf
    "ntpservers":
      - "192.168.1.1"
      - "10.10.10.1"

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: jhu-sheridan-libraries.ntp, ntpservers: [ '10.1.1.1', '192.168.1.1' ] }

License
-------

TBD

Author Information
------------------

- Derek Belrose <dbelrose@jhu.edu>