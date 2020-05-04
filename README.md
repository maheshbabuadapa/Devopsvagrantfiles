# Multiple VM's Vagrantfile

## Vagrant file creates with below items
- 3 VM's with  centos7
- Bridge Connection with Host Machine and Static IP's (Change the Ip according to your Host IP subnet)
- RAM 4 GB CPU 2 CPU
- ssh key genrated and copied to vagrant user
- Ansible, Internet Tools are installed
- I used this setup for Ansible tower install
## Commands to start Vagrant 
```
vagrant up
vagrant ssh master
vagrant halt
vagrant destroy
```