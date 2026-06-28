# Home computer setup

## Setup

Make sure to install any external roles:

```bash
ansible-galaxy role install geerlingguy.docker

```

## Python

Run the ansible playbook:

```bash
ansible-playbook -i inventory.ini master.yaml -e "target_home=/home/cuth target_user=cuth" -K --become
```

