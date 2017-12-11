# ansible-icinga2
Ansible role to install Icinga 2.x with:

* Apache BasicAuth with an AuthUserFile
* MySQL backend

# Playbook to help install Icinga 2.x on CentOS 7

Why? Because Icinga2 + Icingaweb2 is a pain to install and configure. If you just want to take it for a no-hassles test drive, this is good starting point.

## Assumptions

* You have a vanilla install of CentOS 7.
* You've already run a `yum update` and `reboot`
* You've installed ansible: `yum install ansible`
* You've installed git: `yum install git`

## Usage

This Ansible playbook can be used to install Icinga 2.x on localhost and configure with Apache and MySQL. You are free to modify it to do other things of course.

* `git clone https://github.com/cherdt/ansible-icinga2.git`
* `cd ansible-icinga2`
* `ansible-playbook site.yml`
* visit http://icingaadmin:icingaadmin@localhost/icingaweb2/

