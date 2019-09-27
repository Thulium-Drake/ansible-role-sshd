# Ansible role to configure SSH
This role provies a means to configure SSHD with multiple configuration files per host/group.

## Setup
This role uses https://github.com/leapfrogonline/ansible-merge-vars/, which has to be installed on the Ansible Control Host before using this role. You need to install this plugin first, lest you get syntax errors. Installing can be done as follows:

```
pip install ansible-merge-vars
```
