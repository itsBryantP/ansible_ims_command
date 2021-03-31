# ansible_ims_command
This is a simple playbook to run IBM IMS commands via Ansible.
Specify the desired commands to be run in ```ims_commands.yml```

### Dependencies
ibm_zos_ims collection


---
### command to run playbook
```ansible-playbook -i inventory.yml run_command.yaml```