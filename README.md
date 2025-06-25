# Projeto DSList - Intensivão Java Spring

Este projeto consiste em uma aplicação **Back-end Java com Spring**, desenvolvida do início ao fim durante o **Intensivão Java Spring**, com foco em boas práticas, estrutura profissional e integração com banco de dados. A aplicação simula uma lista de jogos e permite operações via API RESTful.

---

## 🚀 Tecnologias Utilizadas

- Java 17
- Spring Boot
- Spring Data JPA
- Banco de dados H2
- Maven
- Postman
- Docker (Compose)
- Git/GitHub

---

## 📚 Conteúdo Abordado

### ✅ Aula 1: Fundamentos e Estruturação

- Conceitos:
- Sistemas web e recursos
- Cliente/servidor, HTTP, JSON
- Padrão **REST** para APIs web
- Estruturação de projeto com Spring REST
- Entidades e ORM (Object-Relational Mapping)
- `Database seeding` (popular dados no banco automaticamente)
- Padrão de camadas: **Controller**, **Service**, **Repository**
- Uso do padrão **DTO (Data Transfer Object)**

---

### ✅ Aula 2: Banco de Dados e Relacionamentos

- Relacionamentos **N-N (muitos-para-muitos)**
- Classe de associação e uso de `@EmbeddedId`
- Escrita de consultas SQL com Spring Data JPA
- Projections (consultas otimizadas com interfaces)

---

### ✅ Aula 3: Ambiente Profissional

- Dicas de currículo e portfólio para desenvolvedores
- Perfis de projeto no mercado
- Ambiente local com **Docker Compose**
- Processo de homologação local
- Deploy com **CI/CD**
- Configuração de **CORS**

---

### ✅ Aula 4: Nível Avançado

- Atingindo o nível **Ultimate Java Spring**
- Design e implementação de **endpoints REST**
- Verbos HTTP e o conceito de **idempotência**

---

## 📌 Como executar o projeto

1. Clone este repositório
2. Abra no IntelliJ, Eclipse ou VS Code com suporte Java
3. Rode o projeto com Spring Boot (classe `main`)
4. Teste os endpoints com Postman ou navegador

---

## 🧪 Exemplos de Endpoints

```http
GET /games
GET /games/{id}
GET /lists
GET /lists/{listId}/games
POST /lists/{listId}/replacement


---

📄 Licença

Este projeto foi desenvolvido por Bianca Cunha durante o curso Intensivão Java Spring.
