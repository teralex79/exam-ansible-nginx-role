Ansible Role: nginx 
===================

Ansible Role that download nginx docker image and generate configuration file for balancing web-apps

Requirements
------------

none

Role Variables
--------------


Dependencies
------------

Uses role docker from git@github.com:teralex79/exam-ansible-docker-role.git

```yaml
- name: Run role Install Docker
  include_role:
    name: docker
```

Example Playbook
----------------

```yaml
- hosts: nginx 
  roles:
    - { role: nginx }
```

License
-------

BSD

Author Information
------------------
This role was created in 2019 by Aleksei Terentev for DevOps Exam
