## Introduce
Jenkins is one of the most popular open-source continuous integration and continuous delivery servers 

## Install Ansible
Install software from various PPA
```sh
$ sudo apt update
$ sudo apt install software-properties-common
```

Next add ppa:ansible/ansible to your system’s Software Source
```sh
$ sudo apt-add-repository ppa:ansible/ansible
```

Update our repos:
```sh
$ sudo apt update
```

Install Ansible:
```sh
$ sudo apt install ansible
```

## Deploy
Go to folder jenkins then:
```sh
$ cd jenkins
$ ansible-playbook -i inventory
```
