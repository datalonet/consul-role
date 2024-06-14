Consul Role
=========

installation & configuration consul agent
Requirements
------------

ansible = 2.16.3 or higher

Role Variables
--------------

version : "1.19.0"

This role is only developed for debian or ubuntu Operating systems


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
- name: install consul agent
  hosts: all
  become: true
  become_user: root
  roles:
    - name: consul-role
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
