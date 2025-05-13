# Desafio Backend OCP

## O Problema

O desafio consiste em criar alguns módulos de um sistema para gerenciamento de OCP.

**Calma lá! O que é OCP?**

> OCP significa Organismo de Certificação de Produtos. É uma entidade que, acreditada pelo INMETRO, realiza a avaliação da conformidade de produtos com normas técnicas e regulamentos, emitindo certificados que garantem a qualidade e segurança dos produtos.

**Mas o que isso tem a ver com o teste?**

Um dos nossos produtos, é um sistema para gerenciamento de OCP, e assim como um sistema ERP, ele possui módulos bastante complexos e interessantes de demonstrar decisões importantes de design, arquitetura e escrita de código.

## Descrição

Sua tarefa, é criar um sistema em backend, utilizando Node.js que sirva como uma API Restful para gerenciar alguns módulos de um sistema OCP para uma empresa fictícia.

O sistema deve ter um sistema de autenticação, e a possibilidade de inserir novos usuários. Deve ter também, uma lista de clientes cadastrados (bem como a possibilidade de inserir novos clientes).

Cada cliente deve possuir uma lista de produtos, e o usuário deve ser capaz de cadastrar novos produtos em um determinado cliente a escolha.

Por fim, o sistema deve gerenciar os processos de certificação da empresa. Cada processo de certificação deve ser feito para um cliente, com N produtos que serão inseridos a escolha do usuário.

Observe que para executar a listagem de produtos, o ideal seria ter também algum mecanismo de filtros para exibir os produtos de um determinado cliente. Ou então, ao realizar a leitura de um cliente específico, já ser capaz de saber quais produtos esse cliente possui.

Além disso, seria interessante aplicar os mesmos filtros para os processos, para saber quais processos de certificação um determinado cliente já possui.

Enfim, use a sua criatividade

## Resumindo

- Desenvolver algum sistema de autenticação
- Listagem, leitura e cadastro de usuários
- Listagem, leitura e cadastro de clientes
- Listagem, leitura e cadastro de produtos
- Listagem, leitura e cadastro de processos de certificação
- Os produtos são cadastrados para um cliente específico
- Além da lista completa de produtos, aplicar filtros para exibir produtos de um cliente específico
- Cada processo de certificação é feito para um cliente, com N produtos

## Requisitos

- **Linguagem de programação:** Utilizar Node.js, com Typescript para escrita do código
- **Framework:** Utilizar o framework NestJS para desenvolvimento da API, ou então uma combinação de Node.js + Express
- **Arquitetura:** seguir uma arquitetura baseada em módulos, contendo controllers, services e repositórios
- **Autenticação:** desenvolver um sistema de autenticação baseado em login através de Token JWT, ou então algum sistema de autenticação mais simples para demonstração
- **ORM:** para este projeto, utilizar um ORM a sua escolha, como por exemplo TypeORM, Prisma, MikroORM, etc
- **Validações:** executar validações de entrada recebidas via API e retornar as mensagens de erro com códigos adequados para a resposta gerada (Not Found, Bad Request, Created, etc)

## Persistência de dados

Para este projeto, utilize um banco de dados SQL a sua escolha, por exemplo, PostgreSQL ou MySQL

## Docker e Docker Compose

Utilize Docker e Docker compose para realizar a orquestração dos containers da aplicação, de modo que seja de fácil execução em qualquer ambiente sem configurações adicionais.

O ideal, seria que em um único Docker Compose estivesse configurado os containers do banco de dados da aplicação, e também da API.

## Instruções para execução

Forneça também um documento com as instruções básicas para executar e testar o projeto, bem como quaisquers configurações de ambiente que devam ser feitas para executar o projeto.

## Documentações de Referência

- [Documentação Node.js](https://nodejs.org/en)
- [Documentação NestJS](https://nestjs.com/)
- [Documentação Express](https://expressjs.com/)
- [Documentação Docker](https://docs.docker.com/)
- [Documentação Docker Compose](https://docs.docker.com/compose/)
- [Documentação TypeORM](https://typeorm.io/)
