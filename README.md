Ansible Playbook: postgresql-nagios-configure
=============================================

Configure Nagios monitoring for PostgreSQL instance

Supported OS:
-------------
* RedHat
* CentOS
* OracleLinux

Requirements
------------

This playbook requires the postgresql-nagios role.

`$ ansible-galaxy install -r roles/requirements.yml`

Examples
--------

    $ ansible-playbook playbook.yml --list-tasks
    $ ansible-playbook playbook.yml --list-tags

Complete Nagios monitoring for PostgreSQL instance configuration

    $ ansible-playbook playbook.yml

Setup password file only

    $ ansible-playbook playbook.yml --tags=postgresql_nagios_passfile

Copy Nagios related scripts

    $ ansible-playbook playbook.yml --tags=postgresql_nagios_copy_scripts

	
License
-------

GPLv3 - GNU General Public License v3.0

Author Information
------------------

This playbook was created in 2018 by [Krzysztof Lewandowski](mailto:Krzysztof.Lewandowski@fastmail.fm).


