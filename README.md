Ansible Role: netbox
=========

An Ansible role for deploying etcd.

Role Variables
--------------

See [`defaults/main.yml`](defaults/main.yml).

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
- hosts: etcd
  roles:
    - role: dschemp.etcd
      become: true
```

License
-------

MIT
