# Projeto Insper Classroom


Feito por Matheus Aguiar e Leonardo Scarlato

## Sobre o projeto

O projeto Insper Classroom consiste em um serviço que visa facilitar a organização e o gerenciamento de aulas, e suas respectivas monitorias e departamentos. Para cada um destes elementos, criamos um microserviço, além de termos implementado dois outros microserviços para autenticação (*Auth*) e gerenciamento de contas (*Account*).

## Arquitetura
<!-- gateway, discovery, etc. -->
O projeto foi desenvolvido utilizando uma arquitetura de microserviços, com o uso de containers *Docker*. Para facilitar a comunicação entre os microserviços, foi implementado um *Gateway*, que redireciona as requisições para o microserviço correto. Além disso, foi implementado um serviço de descoberta (*Discovery*), que permite que os microserviços se registrem e se descubram automaticamente.

Na arquitetura do projeto, temos os seguintes microserviços:

- **Account**: gerenciamento e criação de contas de usuários
- **Auth**: autenticação de usuários e geração de tokens JWT
- **Class**: gerenciamento e criação de aulas
- **Monitoria**: gerenciamento e criação de monitorias
- **Departamento**: gerenciamento e criação de departamentos

Além disso, existem os seguintes serviços auxiliares:

- **Discovery**: serviço de descoberta
- **Gateway**: serviço de redirecionamento de requisições
- **DB**: banco de dados
- **Ops**: serviço de monitoramento

## Tecnologias utilizadas

- **Java**: linguagem de programação utilizada para o desenvolvimento dos microserviços
- **Spring Boot**: framework utilizado para o desenvolvimento dos microserviços
- **Docker**: ferramenta utilizada para a criação de containers
- **Docker Compose**: ferramenta utilizada para a orquestração dos containers
- **Prometheus**: ferramenta utilizada para o monitoramento dos microserviços
- **Grafana**: ferramenta utilizada para a visualização dos dados coletados pelo Prometheus
- **Jenkins**: ferramenta utilizada para CI/CD
- **PostgreSQL**: banco de dados utilizado para armazenar os dados dos microserviços

# Repositórios dos microserviços

### Account

https://github.com/C0D8/insper-class-account

https://github.com/C0D8/insper-class-account-resource

### Auth

https://github.com/C0D8/insper-class-auth

https://github.com/C0D8/insper-class-auth-resource


### Aula

https://github.com/C0D8/insper-class-class

https://github.com/C0D8/insper-class-class-resource

### Monitoria

https://github.com/C0D8/insper-class-monitoria

https://github.com/C0D8/insper-class-monitoria-resource

### Departamento

https://github.com/C0D8/insper-class-departamento

https://github.com/C0D8/insper-class-departamento-resource

### Outros repositórios importantes

#### Docker API

https://github.com/C0D8/insper-class-docker-api

#### Gateway

https://github.com/C0D8/insper-class-gateway

#### Discovery

https://github.com/C0D8/insper-class-discovery

#### Ops

https://github.com/C0D8/insper-class-ops

#### DB

https://github.com/C0D8/insper-class-db
