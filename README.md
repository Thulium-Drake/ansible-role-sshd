[![Build Status](https://drone.element-networks.nl/api/badges/Element-Networks/ansible-role-sshd/status.svg)](https://drone.element-networks.nl/Element-Networks/ansible-role-sshd)

# Ansible role to configure SSH
This role provies a means to install and configure SSHD with:

* multiple configuration files per host/group.
* SSH keys for the root user

NOTE: The default configuration of the server has been hardened significantly! It is NOT compatible with older SSH clients!
It should work on Debian 10+ and RHEL8+.
