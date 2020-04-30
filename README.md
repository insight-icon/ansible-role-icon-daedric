ansible-role-icon-daedric
=========

Ansible role to run a [Deadric](https://github.com/iconation/Daedric) price oracle for the ICON Blockchain. 

Requirements
------------

Ansible > 2.6

Role Variables
--------------

```yaml
network_name: mainnet # Name of network 
use_main_wallet: false # Boolean to use wallet on node instead of generated wallets 
deploy_score: false # Boolean to actually deploy the score 
```

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: ansible-role-icon-daedric
```

License
-------

MIT

Author Information
------------------

Role managed by [insight-icon](https://github.com/insight-icon)
