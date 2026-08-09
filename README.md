# DSCatalog - Projeto de Estudo

## Sobre o Projeto
DSCatalog é um projeto de estudo desenvolvido para praticar e aprimorar habilidades em Java e Spring Boot. A aplicação é um sistema de catálogo que permite gerenciar produtos e categorias, incluindo operações de CRUD e paginação.

## Funcionalidades
- **Gerenciamento de Categorias**: Criar, ler, atualizar e excluir categorias.
- **Gerenciamento de Produtos**: Criar, ler, atualizar e excluir produtos.
- **Paginação e Ordenação**: Recuperar listas paginadas e ordenadas de produtos e categorias.
- **Tratamento de Erros**: Exceções personalizadas para recurso não encontrado e violações de integridade do banco de dados.

## Tecnologias Utilizadas
- **Java 17**
- **Spring Boot 3**
- **Maven**
- **JPA / Hibernate**
- **Banco de Dados H2** (para desenvolvimento e testes)
- **Postman** (para testes da API)

## Arquitetura
O projeto segue uma arquitetura em camadas:
1. **Camada de Controladores (Controller Layer)**: Lida com requisições e respostas HTTP.
2. **Camada de Serviços (Service Layer)**: Contém a lógica de negócios.
3. **Camada de Repositórios (Repository Layer)**: Gerencia a persistência de dados usando JPA.
4. **Camada de Entidades (Entity Layer)**: Representa as tabelas do banco de dados como classes Java.
5. **Camada de DTO (DTO Layer)**: Transfere dados entre as camadas.

## Como Executar
1. Clone o repositório para sua máquina local.
2. Abra o projeto na sua IDE (ex.: IntelliJ IDEA).
3. Execute a aplicação usando o método `main` na classe `DscatalogApplication`.
4. Acesse a API em `http://localhost:8080`.

## Propósito
Este projeto é destinado apenas para fins educacionais. Faz parte de um plano de estudos para melhorar o conhecimento em Java, Spring Boot e desenvolvimento de APIs RESTful.

---