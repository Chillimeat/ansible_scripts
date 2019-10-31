## 

```
ansible-playbook -i hosts common.yaml
ansible-playbook -i hosts docker.yaml

ansible-playbook -i hosts --extra-vars "db_index=120" docker_mariadb.yaml
```