# ansible-python-postgresql-setup
Playbook project with Ansible-based Python+PostgreSQL setup

Prerequisites:

```bash
apt-get install ansible git -y
ansible-galaxy collection install community.postgresql
```

Steps to run:

```
cd ~
ansible-pull -U https://github.com/mkuzmentsov/ansible-python-postgresql-setup.git main.yml
```

