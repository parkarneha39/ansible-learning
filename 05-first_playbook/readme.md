## Steps to write first playbook.

1. Create first_playbook.yml file
2. Create index.html file
    Basic html file
3. Update the servers in inventory.ini file and save it in the same location
4. Run the command

    `ansible-playbook -i inventory.ini first_playbook.yml`

    > ansible-playbook command is used to run any playbook
    > -i mention the inventory file

5. This command will run three tasks on each server

```
    1. First task is always "Gathering Tasks"
    2. Install apache on server
    3. Copy file to remote location
```

6. Verify if apache was installed on VM

    `sudo ps -ef | grep apache2`
    `sudo systemctl status apache2`

7. Verify if file was created on the VM

    ```
    pwd
    ls -ltr
    ```

8. Edit inbound Traffic on EC2
    ```
    Click on Security Group attached to the EC2 instance
    Edit Inbound Rules
    Add Rule --> HTTP --> Anywhere IPV4

9. Paste the public IPV4 address on Chrome and index.html should load