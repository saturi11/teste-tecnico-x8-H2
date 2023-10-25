# Teste Técnico - CRUD de Produtos (Banco de Dados H2)
  Este projeto de exemplo demonstra uma aplicação Java que realiza operações CRUD (Create, Read, Update, Delete) em produtos usando o framework Jakarta Persistence (JPA) e Spring Boot. Neste projeto, utilizamos o banco de dados H2 para fins de desenvolvimento e teste.

## 🚀Visão Geral
Este projeto é composto por um componente principal:

Aplicação Java (Spring Boot):
Implementa as operações CRUD em produtos.
Utiliza o framework Jakarta Persistence (JPA) para mapear objetos Java para entidades de banco de dados.


### 🔧 Configuração e Execução
Certifique-se de ter as ferramentas de desenvolvimento Java instaladas em seu ambiente.

Clone este repositório:

git clone https://github.com/saturi11/teste-tecnico-x8-H2.git

Navegue até o diretório clonado:

cd nome-do-repositorio

Execute a aplicação Java:

./mvnw spring-boot:run

A aplicação estará acessível em http://localhost:8080.

## Endpoints da API

GET /api/produtos: Recupera todos os produtos.

GET /api/produtos/{id}: Recupera um produto pelo ID.

POST /api/produtos: Cria um novo produto.

PUT /api/produtos/{id}: Atualiza um produto existente.

DELETE /api/produtos/{id}: Deleta um produto.

## 🛠️ Construído com
O projeto faz uso das seguintes tecnologias e ferramentas:

*Java: A aplicação é desenvolvida em Java, uma linguagem de programação amplamente utilizada.

*Spring Boot: O framework Spring Boot é usado para simplificar o desenvolvimento de aplicativos Java.

*Jakarta Persistence (JPA): JPA é usado para mapear objetos Java para entidades de banco de dados.

*H2 Database: O banco de dados H2 é um banco de dados relacional em memória amplamente usado para desenvolvimento e teste.

## :scroll: Variáveis de Ambiente

DATABASE_URL: A URL do banco de dados H2. Padrão: jdbc:h2:mem:testdb

DATABASE_USERNAME: Nome de usuário do banco de dados H2. Padrão: sa

DATABASE_PASSWORD: Senha do banco de dados H2. Padrão: password

## :wrench: Configuração do Banco de Dados H2
O banco de dados H2 é um banco de dados em memória, o que significa que os dados não são persistentes após a reinicialização da aplicação. Ele é adequado para desenvolvimento e teste, mas não é recomendado para ambientes de produção.

Para acessar o console do H2:

Certifique-se de que a aplicação Java está em execução.

Abra um navegador da web.

Acesse a seguinte URL: http://localhost:8080/h2-console

Configure as informações de conexão da seguinte forma:

Driver Class: org.h2.Driver

JDBC URL: jdbc:h2:mem:testdb

User Name: sa

Password: password

Clique no botão "Connect" para acessar o console do H2.

Tenha cuidado ao usar o console do H2 e não o utilize em ambientes de produção, pois ele é destinado principalmente ao desenvolvimento e teste.

## ✒️ Autor
* **Gabriel Saturi** - [[Gabriel Saturi](https://github.com/saturi11)]
