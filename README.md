# Baozi Store - API REST

Trabalho de Desenvolvimento Web Back-End (UNINTER).

## Tecnologias
Java 17, Spring Boot 3.3, Spring Data JPA, MySQL (ou H2), Postman.

## Como executar
1. Crie o banco ou deixe o `createDatabaseIfNotExist` cuidar disso.
2. Ajuste usuário e senha em `src/main/resources/application.properties`.
3. Rode `mvn spring-boot:run`. A API sobe em `http://localhost:8080`.

## Endpoints
| Método | Endpoint | Descrição |
|---|---|---|
| POST | /clientes | Cadastra cliente |
| GET | /clientes | Lista clientes |
| GET | /clientes/{id} | Consulta cliente por ID |
| DELETE | /clientes/{id} | Apaga cliente |
| POST | /produtos | Cadastra produto |
| GET | /produtos | Lista produtos |
| GET | /produtos/{id} | Consulta produto por ID |
| DELETE | /produtos/{id} | Apaga produto |
| POST | /pedidos | Registra pedido (valida cliente e produto) |
| GET | /pedidos | Lista pedidos |
| GET | /pedidos/{id} | Consulta pedido por ID |
| DELETE | /pedidos/{id} | Apaga pedido |
