# sysadmin-course
ansible playbook for the sysadmin course - University of Tartu

# Tree
├── inventory
│   └── hosts
├── playbook.yml
└── roles
    └── etais
        └── tasks
            └── main.yml
            
# Objective
This ansible playbook and role do the following:
1) Create user 'scoring'
2) add user 'scoring' ssh key to the authorized_keys, so that it can execute ansible playbooks on itself or from outside
3) Make user 'scoring' passwordless sudo
