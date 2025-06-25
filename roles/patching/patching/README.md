## Role: patching

This role applies system updates and safely manages Apache restarts.

### Features
- Stops Apache before updates
- Uses `wait_for` to simulate reboot
- Starts Apache after
- Fully tagged

### Run with tag:
```bash
ansible-playbook site.yml --tags patching --vault-password-file vault-pass.txt
