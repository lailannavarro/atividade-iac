
### Comandos para execução, após a troca de chaves e preenchimentos dos enedereços IP no arquivo de invetário:

```
sudo ansible-playbook -i inventory jenkins.yml --ssh-common-args='-o StrictHostKeyChecking=no'
sudo ansible-playbook -i inventory rundeck.yml --ssh-common-args='-o StrictHostKeyChecking=no'
sudo ansible-playbook -i inventory lamp.yml --ssh-common-args='-o StrictHostKeyChecking=no'
```

### Screenshots:

<img src="screenshots/Screenshot from 2023-03-17 20-49-58.png">

<img src="screenshots/Screenshot from 2023-03-17 20-50-15.png">

<img src="screenshots/Screenshot from 2023-03-17 20-50-36.png">