# SSH_hardening
 An ansible role for SSH hardening 
 Note:
 Note that this role partially hardens SSH. More control can be added to harden SSH. 
 
# Customise play 

define values in extra_vars.yml file to override default variable values in the role. 

# Execute ansible-playbook

```bash
~$ ansible-playbook deploy_sshd_config.yml --extra-vars "vars_file=./extra_vars.yml"
```

