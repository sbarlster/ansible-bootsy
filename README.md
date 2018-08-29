# ansible-bootsy
A minimal recipie for bootstrapping a VM ready for ansible.

The recipie will:
* connect as root
* create a user
* with an ssh key
* disable password based login for the new and root user

The recipie will not:
* update
* harden
* install any other tools

It's sole purpose is to get to the point where ansible can start its real work - and no more.
