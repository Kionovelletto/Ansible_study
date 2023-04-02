# Ansible_study
Repositório destinado aos estudos no Anbible
![Ansible](https://avatars.githubusercontent.com/u/1507452?s=200&v=4)
## Ansbile
Ansible é um sistema de automação de TI simples. Ele lida com gerenciamento de configuração, implantação de aplicativos, provisionamento de nuvem, execução de tarefas ad hoc, automação de rede e orquestração de vários nós. O Ansible facilita alterações complexas, como atualizações contínuas sem tempo de inatividade com balanceadores de carga. Mais informações no site da Ansible .

## Porque o Ansible?
- Gerencie máquinas rapidamente e em paralelo.
- Evite agentes personalizados e portas abertas adicionais, fique sem agente aproveitando o daemon SSH existente.
- Descreva a infraestrutura em uma linguagem amigável tanto para máquinas quanto para humanos.
- Concentre-se na segurança e na facilidade de auditabilidade/revisão/reescrita do conteúdo.
- Gerencie novas máquinas remotas instantaneamente, sem inicializar nenhum software.
- Permita o desenvolvimento de módulos em qualquer linguagem dinâmica, não apenas em Python.
- Ser utilizável como não root.


## Roteiro para o estudo:
Instalação do Ansible:
```bash
1_Install_Ansible.txt
```
Inventário de servidores:
```bash 
2_inventory.cfg
```
Testando conectividade com servidores:
```bash 
3_ping_servers.txt
```
Gerenciando usuários nos servidores remotos:
```bash 
4_adhoc_criando_usuarios_srv_remoto.txt
```
Gerenciando pacotes nos servidores remotos:
```bash 
4_adhoc_gerenciando_pacotes_srv_remoto.txt
```
Instalando e configurando o Nginx no servidores:
```bash 
5_playbook_install_nginx_iptables.yaml
```


Sources:
- https://github.com/ansible/ansible
- https://www.ansible.com/


