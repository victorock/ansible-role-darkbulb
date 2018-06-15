Ansible Darkbulb
=========

Simple Role to Deploy Darkbulb Network.

Requirements
------------

```YAML
darkbulb_user: "darkbulb"
darkbulb_homedir: "/home/darkbulb"
darkbulb_ansible: "yes"
darkbulb_cockpit: "yes"
darkbulb_libvirt: yes
darkbulb_vagrant: "no"
darkbulb_virtualbox: "no"
```

Role Variables
--------------

None

Dependencies
------------

None

Example Playbook
----------------

```YAML
- name: "Deploy Ansible Tower by Red Hat"
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
