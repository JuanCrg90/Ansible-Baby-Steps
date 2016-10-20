# Ansible baby steps

This repo contains very basic playbooks for ansible shell commands. I hope update someday.

I tested in a digital ocean instance using the root user and a non-root user (user `-ask-become-pass` flag)

```sh
ansible-playbook <playbook-name>.yml --ask-pass 
ansible-playbook <playbook-name>.yml --ask-pass --ask-become-pass
```
