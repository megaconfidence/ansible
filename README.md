# ansible

## Modules
### cli-apps.yml
```sh
ansible-playbook --ask-become-pass  cli-apps.yml
```

### keys.yml
```sh
ansible-playbook --vault-id @prompt keys.yml
```

### desktop-apps.yml
```sh
ansible-galaxy collection install community.general
```
