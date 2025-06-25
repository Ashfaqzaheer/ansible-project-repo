## Role: apache_web

Installs Apache and replaces the default index page with a dynamic template.

### Template Variables
- site_title
- description
- env_type
- ansible_hostname (auto from facts)

### Sample Inventory
In `group_vars/webservers.yml`:
```yaml
site_title: "Staging Site"
description: "This server is part of the staging environment"
env_type: "stage"
