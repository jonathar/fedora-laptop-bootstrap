# Linux Laptop Bootstrap

## Setup ssh key

Make sure to enter a password at the prompt.

```
$> ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
```

## Install Ansible and python

```
$> dnf install -y python2 ansible
```

## Run the playbook

```
$> ansible-playbook --ask-become-pass -i local site.yml
```
