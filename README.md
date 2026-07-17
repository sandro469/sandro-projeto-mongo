# Workshop MongoDB - API REST 🍃

Projeto desenvolvido utilizando Java e Spring Boot com integração ao banco de dados MongoDB.

## Objetivo do Projeto

Desenvolver uma API REST aplicando conceitos de desenvolvimento Back-end,
persistência de dados e organização em camadas, utilizando MongoDB como banco de dados NoSQL.

## Tecnologias Utilizadas

- Java 21
- Spring Boot
- MongoDB
- Maven
- Postman
- Git/GitHub

## Arquitetura do Projeto

O projeto foi desenvolvido utilizando uma estrutura organizada em camadas:

- Domain
- Repository
- Service
- Resource (Controller)
- DTO
- Exception Handler

## Conceitos Aplicados

- API REST
- CRUD de usuários
- MongoDB e documentos NoSQL
- DTO (Data Transfer Object)
- Repository Pattern
- Service Layer
- Injeção de dependências
- Tratamento global de exceções
- ResponseEntity
- Integração entre aplicação e banco de dados

## Funcionalidades

✅ Buscar todos os usuários  
✅ Buscar usuário por ID  
✅ Criar usuário  
✅ Atualizar usuário  
✅ Remover usuário  
✅ Buscar posts de um usuário  

## Endpoints

GET /users

GET /users/{id}

GET /users/{id}/posts

POST /users

PUT /users/{id}

DELETE /users/{id}

## Aprendizados

Durante o desenvolvimento foram praticados conceitos de desenvolvimento Back-end,
criação de APIs REST, integração com banco de dados NoSQL e organização de projetos utilizando Spring Boot.
