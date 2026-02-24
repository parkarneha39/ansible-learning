## Use Galxy Role from Ansible Galaxy docummentation
## Install Docker on the machines

>NOTE: I have made the changes under first_code folder, as it was just a small change of adding the role to main.yml file. 
>Keeping the readme.md file separate so I know what changes were made. 


1. Follow this link:

    https://galaxy.ansible.com/ui/standalone/roles/bsmeding/docker/install/

2. Execute the command mentioned in the documentation
3. In the main.yml file, add new role
    roles:
     - bemeding.docker
4. To find all the roles installed, run this command
    `ls ~/.ansible/roles `
5. `ansible-playbook -i inventory.ini first_playbook.yml`
