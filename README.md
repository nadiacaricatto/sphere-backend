# 🌐 Sphere — Backend

> API REST de uma plataforma desenvolvido por mim que mistura conceitos e funcionalidades de blog com rede social, com autenticação JWT, documentação Swagger e testes automatizados!

---

## 📖 Sobre o Projeto

> A **Sphere** é uma aplicação fullstack que combina a liberdade de um blog com as conexões e interações de uma rede social! 
> 
> Este repositório contém o **backend**: uma API REST completa com autenticação JWT, gerenciamento de usuários, postagens e temas, documentação Swagger e suporte a Docker.

---

## ✨ Funcionalidades

**Usuários**
- 📝 Cadastro de novo usuário
- 🔐 Login com autenticação JWT
- ✏️ Atualização de perfil

**Postagens**
- 📋 Listar todas as postagens
- 🔍 Buscar postagem por ID e por título
- ➕ Criar nova postagem
- ✏️ Atualizar postagem
- 🗑️ Deletar postagem

**Temas**
- 📋 Listar todos os temas
- 🔍 Buscar tema por ID e por descrição
- ➕ Criar novo tema
- ✏️ Atualizar tema
- 🗑️ Deletar tema

---

## 🛠️ Tecnologias

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Spring Security](https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=spring-security&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

- Spring Boot
- Spring Security + JWT
- Spring Data JPA + Hibernate
- MySQL
- Swagger (SpringDoc OpenAPI)
- Docker
- JUnit (testes automatizados)
- Dotenv (variáveis de ambiente)
- Perfis dev/prod separados

---

## 🚀 Como Rodar

**Pré-requisitos:** Java 17+, MySQL, Maven

```bash
# Clone o repositório
git clone https://github.com/nadiacaricatto/blogpessoal_spring.git

# Entre na pasta
cd blogpessoal_spring

# Configure as variáveis de ambiente no arquivo .env

# Rode o projeto (perfil dev)
./mvnw spring-boot:run -Dspring-boot.run.profiles=dev
```

A API estará disponível em `http://localhost:8080`

**Documentação Swagger:** `http://localhost:8080/swagger-ui.html`

**Ou rode com Docker:**
```bash
docker build -t sphere-backend .
docker run -p 8080:8080 sphere-backend
```

---

## 🧪 Testes

```bash
./mvnw test
```

---

## 🔗 Projeto Relacionado

Este backend foi desenvolvido em conjunto com o frontend do Sphere:

👉 [blogpessoal_react](https://github.com/nadiacaricatto/blogpessoal_react)

---

## 👩‍💻 Autora

Desenvolvido por **Nádia Caricatto**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nadiacaricatto/)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nadiacaricatto)

---

*Desenvolvido durante o Bootcamp da **Generation Brasil**, com foco em desenvolvimento backend com Spring Boot, Spring Security, JWT e boas práticas de API REST.*
