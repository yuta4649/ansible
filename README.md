# ansible

## 実行手順
```bash
# mac/linux
os=mac
# linux-ca.yml/mac-mini.yml ...
playbook=macbook-air.yml
# keycloak/pv_pvc ...
role=keycloak

ansible-playbook -i inventories/$os playbooks/$playbook -v --diff --tags $role
```
