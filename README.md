# sysadmin-course
ansible playbook for the sysadmin course - University of Tartu

# Project tree

this-repository/
 * [roles](/roles)
   * [etais](/roles/etais)
   * [tasks](/roles/etais/tasks)
   * [main.yml](/roles/etais/tasks/main.yml)
 * [playbook.yml](/playbook.yml)
 * [inventory](/inventory)
     * [hosts](/inventory/hosts)
            
# Objective
This ansible playbook and role do the following:
1) Create user 'scoring'
2) add user 'scoring' ssh key to the authorized_keys, so that it can execute ansible playbooks on itself or from outside
3) Make user 'scoring' passwordless sudo
