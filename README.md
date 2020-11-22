Ansible Roundcube
=========

Simple role for install roundcube on webserver

Requirements
------------

Webserver and Mailserver installed.

Role Variables
--------------

Any variables that are in defaults/main.yml

Example Playbook
----------------

```yml
- hosts: servers
  become: "{{ become | default('yes') }}"
  roles:
    - { role: mikysal78-roundcube, tags: roundcube }
```

License
-------

GPL

Author Information
------------------

- [MikySal78](https://github.com/mikysal78)
