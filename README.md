# API de Restaurante – Spring Boot 4 & Java 25

Este projeto é uma API REST construída com Spring Boot 4.0 e Java 25, focada em oferecer uma arquitetura limpa, modular e preparada para aplicações modernas. O objetivo é gerenciar um cardápio digital, permitindo o cadastro de categorias e pratos, além de consultas filtradas e ordenações comuns ao domínio gastronômico.

A aplicação segue boas práticas de engenharia, utiliza camadas bem definidas (Controller, Service, Repository) e explora recursos do Java 25, como records, pattern matching e aprimoramentos no modelo de concorrência.

---

## Arquitetura

A API segue uma arquitetura em camadas:

- **Controller**: expõe endpoints REST e padroniza respostas.
- **Service**: centraliza regras de negócio e validações.
- **Repository**: abstrai o acesso ao banco via Spring Data JPA.
- **Entities**: modelos de domínio (Categoria, Prato).
- **DTOs**: entrada e saída de dados com validação.

Essa organização facilita manutenção, testes e evolução do código.

---

## Funcionalidades

- Cadastro de categorias  
- Cadastro de pratos vinculados a categorias  
- Atualização e remoção de registros  
- Listagem geral ou filtrada por categoria  
- Busca por nome com paginação  
- Consulta de pratos ordenados por preço  
- Estrutura preparada para relatórios e extensões

---

## Tecnologias Utilizadas

- Java 25  
- Spring Boot 4.0  
- Spring Web  
- Spring Data JPA  
- MySQL
- Spring Boot Test  
- Lombok (opcional)  
- Swagger (opcional)
