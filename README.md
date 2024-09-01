# Notificação de Acidentes

Este é um projeto desenvolvido em Spring Boot para gerenciar a notificação de acidentes em uma cidade inteligente. O sistema visa melhorar a resposta a emergências, permitindo o registro, acompanhamento e notificação de acidentes, bem como a coordenação de recursos, como ambulâncias, de forma eficiente.

## Funcionalidades

- **Registro de Acidentes**: Captura e armazena detalhes sobre acidentes ocorridos.
- **Notificação**: Envia notificações em tempo real para os usuários cadastrados e serviços de emergência.
- **Gestão de Recursos**: Coordena a disponibilidade e alocação de recursos, como ambulâncias, para atender os acidentes.
- **Acompanhamento de Investigações**: Permite o acompanhamento do progresso das investigações relacionadas aos acidentes.

## Tecnologias Utilizadas

- **Java 22 **
- **Spring Data JPA** para interação com o banco de dados.
- **Spring Security** para autenticação e autorização.
- **Oracle** para armazenamento de dados.
- **Postman** para envio das requisições https.

## Arquitetura do Projeto

O projeto segue uma arquitetura em camadas, dividida nas seguintes partes:

- **Controller**: Camada responsável por gerenciar as requisições HTTP.
- **Service**: Camada onde estão implementadas as regras de negócio.
- **Repository**: Camada responsável pela interação com o banco de dados Oracle.
- **Model**: Camada que define as entidades e modelos de dados.

# Autores
| [<img loading="lazy" src="https://avatars.githubusercontent.com/u/127707049?v=4" width=115><br><sub>Rafael Feitosa Santos</sub>](https://github.com/Rafael-Feitosa-santos) | 
| :---: |
