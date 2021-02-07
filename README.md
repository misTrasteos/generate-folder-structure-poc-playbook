# Context
This is PoC about using Ansible to provision a folder structure, files and its contents from a yml file.

There is yml file including artists, songs and its lyrics

# How to ...
**How to create a role**
```
ansible-galaxy init generate-folder-structure-poc-role
```
**How to execute a playbook**
```
ansible-playbook generate-folder-structure-poc-playbook.yml
```
# output

```
output
├── Barón Rojo
│   ├── Hijos de Caín.txt
│   └── Los rockeros van al infierno.txt
└── Green Day
    ├── Boulevard of Broken Dreams.txt
    └── Oh Love.txt
```

# Links
## Ansible reference
* [File module](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/file_module.html)
* [subelements lookup](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/subelements_lookup.html)
* [Copy module](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/copy_module.html)
## Samples from the internet
* [Create an Ansible role](https://www.golinuxcloud.com/create-ansible-role-with-example-playbooks)