# Ansible Collection - knorrkator.etcd

Ansible Collection to manage etcd on Raspberry Pi / ARM

# Install
Put following in your requirements.yml

```yaml
collections:
  - name: https://github.com/knorrkator/ansible-collections-etcd.git
    type: git
    version: main   # I actually recommend to pin it to a git commit id
```

And run
```bash
ansible-galaxy install -r requirements.yml
```