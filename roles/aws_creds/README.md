## Role: aws_creds

This role creates AWS credentials and config files using Vault.

### Requirements
- Use `group_vars/all/vault.yml` encrypted with Ansible Vault.
- Use `vault-pass.txt` to decrypt.

### Example
```bash
ansible-playbook site.yml --ask-vault-pass
# or
ansible-playbook site.yml --vault-password-file vault-pass.txt
