# ansible
### Ansible manual command : using this, we can execute one command at a time.
ansible all -i inventory -e ansible_user=centos -e ansible_password=DevOps321 -m shell -a "df -h"


-i inventory file
-e extra or environment variables
ansible_user : special variable name for the user-account to use
ansible_password : special variable name for the user-account password to use
-m : name of the module

# List
# A list of tasty fruits
---
    - Apple
    - Orange
    - Strawberry
    - Mango