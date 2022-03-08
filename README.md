Role Name
=========

For Regional Win11React

Reference: https://github.com/blueedgetechno/win11React

Requirements
------------

NEED DOCKER Installed (use the docker playbook in repo)


Example Playbook
----------------
```
- hosts: "{{ host }}"
  gather_facts: no
  roles:
    - role: "{{ role }}"root@ansible:/etc/ansible# 
```

Example of how to use your role
--------------------------------
```
ansible-playbook playbook.yml -e host=ubuntu -e role=win11
```


Playbook Tasks main.yml stop/start example
---------------------------------------
```
- name: Linux - Start/Restart Win11React
  systemd:
    name: win11react
    #state: stopped
    state: started
```

License
-------

BSD

Author Information
------------------
Dfir-jesseee && Axl


License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
