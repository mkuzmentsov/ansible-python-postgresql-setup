# ansible-python-postgresql-setup
Playbook project with Ansible-based Python+PostgreSQL setup

Prerequisites:

```bash
- sudo apt-get install ansible git -y
- sudo ansible-galaxy collection install community.postgresql
```

Steps to run:

```
cd ~
sudo ansible-pull -U https://github.com/mkuzmentsov/ansible-python-postgresql-setup.git main.yml
```

