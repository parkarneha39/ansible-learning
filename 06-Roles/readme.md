1. Create the Role
    `ansible-galaxy role init httpd`
2. Copy the tasks under first_playbook.yml to file httpd/tasks/main.yml
    `Change the file location to files/index.html`
3. Move index.html file under httpd/files
4. Edit first_playbook.yml file
    ```
    roles:
    httpd
    ```
5. Execute this command
    `ansible-playbook -i inventory.ini first_playbook.yml`