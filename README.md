# sysadmin-course
ansible playbook for the sysadmin course - University of Tartu

# Project tree

this-repository/
 * [roles](ansible/roles)
   * [etais](ansible/roles/etais)
   * [tasks](ansible/roles/etais/tasks)
   * [main.yml](ansible/roles/etais/tasks/main.yml)
 * [playbook.yml](ansible/playbook.yml)
 * [inventory](ansible/inventory)
     * [hosts](ansible/inventory/hosts)
            
# Objective
This ansible playbook and role do the following:
1) Create user 'scoring'
2) add user 'scoring' ssh key to the authorized_keys, so that it can execute ansible playbooks on itself or from outside
3) Make user 'scoring' passwordless sudo
