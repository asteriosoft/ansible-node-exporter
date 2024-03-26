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
    version_exporter: '1.5.0'
    exporter_arch: 'amd64'

  roles:
    - node-exporter
```

