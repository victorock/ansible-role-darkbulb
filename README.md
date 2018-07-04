Ansible Darkbulb
=========

Simple Role to Deploy Darkbulb Network.

Requirements
------------

None

Role Variables
--------------

```YAML
darkbulb_homedir: "~/.darkbulb"
darkbulb_ansible: "yes"
darkbulb_cockpit: "yes"
darkbulb_libvirt: yes
darkbulb_vagrant: "no"
darkbulb_virtualbox: "no"
```

Dependencies
------------

victorock.cockpit
victorock.libvirt
victorock.gns3_server

Example Playbook
----------------

```YAML
- name: "Deploy Darkbulb"
  hosts: darkbulb
  become: true

  roles:
    - victorock.darkbulb
```

License
-------

GPLv3

Author Information
------------------

Victor da Costa
