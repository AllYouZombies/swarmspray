# Swarmspray

```shell
cp inventory/example-hosts.yml inventory/hosts.yml
cp group_vars/all/example-all.yml group_vars/all/all.yml
```

Edit `inventory/hosts.yml` and `group_vars/all/all.yml` to match your environment.

```shell
ansible-playbook -v playbooks/main.yml
```