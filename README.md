# docker-play
A simple playbook to install docker on linux machines.

# :construction: 
## this currently only works on debian based distributions

feel free to make a PR if you have a playbook for another distro


# Usage 

 - add your server or server IP's to the `inventory file`
 - in the `ansible.cfg`  enter the name of the remote user 

now run with `ansible-playbook run -K `

it would prompt you for your ssh password, once you enter it you are good to go

### i hope i saved you some time :rocket:




