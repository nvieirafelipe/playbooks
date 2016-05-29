# Cookbooks

Add localhost to ansible hosts

```
#/etc/ansible/hosts

localhost ansible_connection=local

```

## Run

```
ansible-playbook cookbook.yml --ask-become-pass --extra-vars="user=nvieirafelipe"
```

## Reference
[cdown/ansible-personal](https://github.com/cdown/ansible-personal)
[osxstrap/ansible-dotfiles](https://github.com/osxstrap/ansible-dotfiles)
