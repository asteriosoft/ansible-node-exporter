node-exporter
=========

Role for node-exporter service installation.

Role Variables
--------------

To do

Example Playbook
----------------
```
- hosts: servers
  become: yes
  gather_facts: yes

  vars:
    node_exporter_version: '1.5.0'
    node_exporter_arch: 'amd64'

  roles:
    - node-exporter
```

