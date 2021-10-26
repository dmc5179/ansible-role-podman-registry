podman-registry
=========

Ansible role to install and configure a docker registry with podman

Requirements
------------

- Install require pip modules

```
python3 -m pip install --user -r requirements.txt
```

- Install required ansible collections

```
ansible-galaxy collection install -r requirement.yml
```


Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

- hosts: localhost
  roles:
    - dmc5179.ansible_role_podman_registry


```
ansible-playbook -i 'localhost' registry.yml
```

License
-------

BSD

Author Information
------------------

Dan Clark <danclark@redhat.com>
