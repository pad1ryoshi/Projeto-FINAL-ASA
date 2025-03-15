# Projeto-FINAL-ASA

Projeto final da disciplina de Administração de Sistemas Abertos.

## Descrição

O objetivo deste projeto é provisionar uma máquina virtual (VM) com o Vagrant, configurar o ambiente usando Ansible e implantar uma aplicação WordPress utilizando Docker Compose. O ambiente inclui:

- **Vagrant**: Para criar e gerenciar a VM.
- **Ansible**: Para automatizar a configuração do sistema e a instalação do Docker.
- **Docker**: Para criar e gerenciar os containers da aplicação.
- **WordPress**: Aplicação principal, servida pelo Nginx como proxy reverso.
- **MySQL**: Banco de dados para o WordPress.
- **Nginx**: Sendo utilizado como Proxy da camada 4.

## Requisitos

- **Vagrant**: [Instalação do Vagrant](https://www.vagrantup.com/downloads)
- **VirtualBox**: [Instalação do VirtualBox](https://www.virtualbox.org/wiki/Downloads)
- **Ansible**: [Instalação do Ansible](https://docs.ansible.com/ansible/latest/installation_guide/index.html)

## Execução

```
1. git clone https://github.com/pad1ryoshi/Projeto-FINAL-ASA.git
```
```
2. vagrant up
```
```
3. acesse o servidor web no seguinte endereço: http://192.168.57.10:8080
```
