**site.md — Main Ansible Playbook**

This playbook defines the primary configuration for the CraftRoast server environment.

Hosts: craftroast
Privilege Escalation: become: true
Loads shared user-related variables from: ../vars/users.yml
Roles Applied:  
    - commmon
    - users
    - docker
    - bagisto
    - grafana
