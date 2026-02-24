## Ansible Role command
`ansible-galaxy role init <name of the role>`

## Ansible Galaxy documentation
 https://galaxy.ansible.com/ui/standalone/roles/

## Directory Structure of an Ansible Role

An Ansible role follows a specific directory structure:

```
<role_name>/
  ├── defaults/
  │   └── main.yml
  ├── files/
  ├── handlers/
  │   └── main.yml
  ├── meta/
  │   └── main.yml
  ├── tasks/
  │   └── main.yml
  ├── templates/
  ├── vars/
      └── main.yml
```