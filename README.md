# SSH authorisation with ansible

## Installation steps

- Go to you ansible project folder
- Add following to your requirements file

```
- src: https://github.com/PHKA-ZIM/ansible-role-ssh_authorisation
  name: ansible-role-ssh_authorisation
```

- Install to project roles path
```
ansible-galaxy install -r requirements.yml --roles-path ./roles
```

## Use ansible-role-ansible-role-ssh_authorisation

- Import role and override role variables, e.g.
```
- name: Authorise ssh keys
  roles:
    - role: ansible-role-ssh_authorisation
```
