# Infrastructure Integration using Code for Linux

This Repository is Infrastructure Integration for Linux using "Ansible" IaC.

## USAGE

`ansible-playbook -i hosts playbook_for_Linux.yml --ask-vault-pass`

## Note

- "hosts" File is needed
- "group_vars" Dir and variable Files(./group_vars/*.yml) is needed
- It is recommended to variable Files(./group_vars/*.yml) are  encrypted
