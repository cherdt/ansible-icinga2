# ansible-icinga2
Ansible role to install Icinga 2.x

Note that this is currently a work-in-progress.

# Playbook to help install Icinga 2.x on CentOS 7

Why? Because it's a pain to install but maybe you just want to take it for a test drive.

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

