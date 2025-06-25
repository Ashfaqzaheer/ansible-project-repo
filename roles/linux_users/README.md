## Role: linux_users

Creates local Linux users and configures their public SSH keys.

### Example Variables (`group_vars/all/users.yml`)
```yaml
users:
  - name: alice
    shell: /bin/bash
    pubkey: "ssh-rsa AAAAB3... alice@laptop"
