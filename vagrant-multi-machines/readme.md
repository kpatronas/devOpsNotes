# Vagrantfile - multimachine deployment template

## Prerequisites
- Vagrant: tested with version 2.2.7
- Virtualbox: tested with version 5.2.34
- vagrant-hostmanager plugin: tested with version 1.8.9
- You need to create SSH keys

## Things to note:
- vagrant guests are reachable from the host or other vagrant guests with their hostnames (vagrant-hostmanager)
- vagrant will use your public key to be appended to the authorized_keys for the 'vagrant' user
