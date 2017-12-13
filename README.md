# ansible-IdealniServer
Ansible provisioning of Ubuntu 16.04

## Instructions

On client:

```
apt-get install git ansible sudo
adduser <user> sudo
reboot
```

On server:

```
apt-get install python
```

Execute by running

```
./run.sh --extra-vars "ansible_sudo_pass=<password>"
```

