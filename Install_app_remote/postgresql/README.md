# Instalando o PostgreSQL com Ansible

## Requisitos para executar o playbook em seu equipamento local:
```bash
apt install postgresql postgresql-contrib
ansible-galaxy collection install community.postgresql
```


### Execute o comando para validar as configurações:
```bash
ansible-playbook install_potsgresql.yml --syntax-check
```

### Agora faça o deploy do playbook:
```bash
ansible-playbook install_potsgresql.yml -i hosts.ini --user=<USER_COM_PRIVILEGIOS>
```