## Inventory Files

These files store the server list to which the control node will talk to.

There are 2 types:

## 1. Inventory.ini
   - etc/ansible/hosts (default location)
   - ubuntu@<PUBLIC-IP> (store the servers in this format)

## 2. Inventory
   - YAML files
  
Adhoc command:
  `ansible -i inventory.ini -m ping all`  (all - indicates all the servers)
