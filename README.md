# ansible-cancer-usegalaxy-org
Playbook for cancer.usegalaxy.org

## Installation

### Requirements

ansible v2.10.3 or higher and Ansible module dependencies.

```
pip install --upgrade "ansible>=2.10.3" netaddr
ansible-galaxy collection install -r requirements.yml -p collections
ansible-galaxy role install -r requirements.yml -p roles
```