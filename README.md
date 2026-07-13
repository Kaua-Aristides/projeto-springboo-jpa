# Primeiro projeto API REST com Spring Boot

## 📖 Sobre o projeto

Este projeto foi desenvolvido durante meus estudos de **Spring Boot**, acompanhando aulas e realizando adaptações para consolidar os conhecimentos na criação de APIs REST utilizando Java.

A aplicação simula um sistema de e-commerce, permitindo o gerenciamento de usuários, produtos, categorias, pedidos e pagamentos, utilizando boas práticas de desenvolvimento com Spring Boot e JPA/Hibernate.

---

## 🚀 Tecnologias utilizadas

* Java
* Spring Boot
* Spring Data JPA
* Hibernate
* Maven
* Banco de dados H2 (ambiente de testes)
* Jackson
* Postman

---

## 📚 Conceitos praticados

Durante o desenvolvimento deste projeto foram aplicados diversos conceitos importantes, entre eles:

* Criação de APIs REST
* Arquitetura em camadas (Resources, Services, Repositories e Entities)
* Persistência de dados com JPA/Hibernate
* Mapeamento objeto-relacional (ORM)
* Relacionamentos entre entidades:

  * One-to-Many
  * Many-to-One
  * Many-to-Many
  * One-to-One
* Chave composta com `@EmbeddedId`
* Enum para controle do status dos pedidos
* Injeção de dependências com `@Autowired`
* Tratamento de exceções personalizado
* Utilização de `ResponseEntity`
* Operações CRUD
* População automática do banco de dados para testes (`CommandLineRunner`)

---

## 📂 Estrutura do projeto

O projeto está organizado em camadas:

* **Entities** → Modelagem das entidades do sistema.
* **Repositories** → Comunicação com o banco de dados através do Spring Data JPA.
* **Services** → Regras de negócio da aplicação.
* **Resources (Controllers)** → Endpoints da API REST.
* **Exceptions** → Tratamento global de erros da aplicação.
* **Config** → Configuração e carga inicial de dados para testes.

---

## 🔗 Endpoints disponíveis

### Usuários

* GET `/users`
* GET `/users/{id}`
* POST `/users`
* PUT `/users/{id}`
* DELETE `/users/{id}`

### Produtos

* GET `/products`
* GET `/products/{id}`

### Categorias

* GET `/categories`
* GET `/categories/{id}`

### Pedidos

* GET `/orders`
* GET `/orders/{id}`

---

## 🎯 Objetivo

Este projeto teve como objetivo aprender os fundamentos do desenvolvimento de APIs REST com Spring Boot, praticando desde a modelagem das entidades até a implementação dos serviços, repositórios, controladores e tratamento de exceções.

---

## 📈 Aprendizados

Com este projeto consegui praticar:

* Organização de projetos Spring Boot
* Criação de APIs REST
* Modelagem de banco de dados com JPA
* Relacionamentos complexos entre entidades
* Operações CRUD
* Tratamento de erros
* Uso do Maven para gerenciamento de dependências
* Testes dos endpoints utilizando o Postman
