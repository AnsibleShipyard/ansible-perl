ansible-perl
================

ansibleshipyard/ansible-perl

[![Build Status](https://travis-ci.org/AnsibleShipyard/ansible-perl.svg?branch=master)](https://travis-ci.org/AnsibleShipyard/ansible-perl)

[Galaxy Role](https://galaxy.ansible.com/list#/roles/3227)

[Dockerfile](https://registry.hub.docker.com/u/ansibleshipyard/ansible-perl/)


Usage
-----

docker pull ansibleshipyard/ansible-perl

OR

docker run -t -i ansibleshipyard/ansible-perl bash


Notes
-----

Also installs `cpanminus` and `perlbrew` if necessary.


Requirements
------------

Role requires Ansible.


Role Variables
--------------

TODO


Dependencies
------------

None.


Example Playbook
----------------

To install `perl-5.20.2`:

    - hosts: servers
      roles:
         - { role: username.rolename,  perl_min_version: 5.020002, perl_min_version_label: perl-5.20.2 }


License
-------

Apache2


Author Information
------------------

- @JasonGiedymin
