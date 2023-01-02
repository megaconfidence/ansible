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
#install module for flathub
ansible-galaxy collection install community.general
ansible-playbook --ask-become-pass desktop-apps.yml
```
