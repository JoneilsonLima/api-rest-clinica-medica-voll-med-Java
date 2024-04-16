# Projeto: API Rest para Clínica Médica Voll Med (Em desenvolvimento)

## Descrição Geral

Este projeto tem como objetivo desenvolver uma API Restful para uma clínica médica fictícia chamada Voll Med. A API permitirá o cadastro, gerenciamento e consulta de informações relacionadas a médicos, pacientes e agendamento de consultas.

## Funcionalidades

### Médicos

- Cadastro de novos médicos com informações como nome completo, especialidade, CRM, e-mail, telefone, endereço (logradouro, número, complemento, cidade).
- Listagem de médicos cadastrados.
- Atualização de informações de médicos existentes.
- Exclusão de médicos do sistema.

### Pacientes
- Cadastro de novos pacientes com informações como nome completo, e-mail, telefone, endereço (logradouro, número, complemento, cidade).
- Listagem de pacientes cadastrados.
- Atualização de informações de pacientes existentes.
- Exclusão de pacientes do sistema.

### Consultas
- Agendamento de novas consultas associando médico e paciente.
- Listagem de consultas agendadas.
- Cancelamento de consultas previamente agendadas.

### Tecnologias Utilizadas
- `Spring Boot 3`: Framework para desenvolvimento da API
- `Java 17`: Linguagem de programação utilizada
- `Lombok`: Biblioteca para simplificação de código
- `MySQL`: Banco de dados para armazenamento das informações
- `Flyway`: Ferramenta de migração para controle de versionamento do banco de dados
- `JPA/Hibernate`: Camada de persistência e mapeamento objeto-relacional
- `Maven`: Gerenciador de dependências e build do projeto
- `Insomnia`: Ferramenta para testes e simulação de requisições à API

### Recursos Adicionais
- `Padronização de Retornos`: Todos os controllers da API serão padronizados para garantir consistência nos retornos.
- `Códigos HTTP`: Utilização adequada dos códigos HTTP para representar o estado das requisições.
- `Spring Security`: Adição do módulo Spring Security para segurança da API.
- `Autenticação`: Implementação de um mecanismo de autenticação na API.
- `Controle de Acesso`: Realização do controle de acesso na API.
- `JWT (Json Web Token)`: Utilização de JWT para controle de acesso na API.
- `Regras de Negócio`: Isolamento de códigos de regras de negócio em uma aplicação.
- `Princípios SOLID`: Implementação dos princípios SOLID para um código mais limpo e manutenível.
- `Documentação OpenAPI`: Documentação da API seguindo o padrão OpenAPI.
- `Testes Automatizados`: Escrita de testes automatizados utilizando Spring Boot.
- `Build e Deploy`: Realização do build da aplicação e utilização de variáveis de ambiente para preparar a aplicação para o deploy.

### Metas do Projeto
- Desenvolver uma API Rest completa utilizando Spring Boot 3
- Implementar CRUDs para Médicos, Pacientes e Consultas
- Utilizar Flyway para controle de versionamento do banco de dados
- Implementar validações utilizando Bean Validation
- Implementar mecanismos de paginação e ordenação dos dados da API
- Garantir segurança, autenticação e controle de acesso na API
- Seguir os princípios SOLID e padronizar retornos e códigos HTTP
- Documentar a API conforme o padrão OpenAPI
- Escrever testes automatizados e realizar o build e deploy da aplicação


Este projeto visa proporcionar uma solução robusta e eficiente para a gestão de informações em uma clínica médica, aplicando as melhores práticas de desenvolvimento e utilizando tecnologias atualizadas e de alta qualidade.
