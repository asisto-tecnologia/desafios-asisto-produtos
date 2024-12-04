# Desafio Backend Boost

O desafio Backend Boost consiste em criar um sistema para gerenciamento de uma loja.

O sistema deve compreender as atividades do administrador do sistema, ou seja, supor que o usuário que utiliza o sistema é o dono da loja que necessita de cadastrar produtos, clientes e lançar um novo pedido no sistema.

Não considerar a solução como uma loja e-commerce, por exemplo, onde também existiria o escopo do usuário que se cadastra na loja. Para este projeto, considerar apenas o escopo do administrador da loja.

O sistema deve ser implementado como uma API, com endpoints para gerenciamento dos recursos relacionados à loja.

## Requisitos

### Backend

- **Linguagem de programação:** Utilize a linguagem JavaScript através do runtime Node.js, utilizando TypeScript para escrita do código
- **Framework:** Utilizar o framework NestJS para desenvolvimento da API ou a combinação Node.js + Express
- **Arquitetura:** seguir uma arquitetura baseada em módulos, contendo controllers, services e repositórios
- **Autenticação:** desenvolver um sistema de autenticação baseado em e-mail + senha e login através de Token JWT
- **ORM:** para este projeto, utilizar um ORM a sua escolha, como por exemplo TypeORM, Prisma, MikroORM, etc
- **Validações:** executar validações de entrada recebidas via API e retornar as mensagens de erro com códigos adequados para a resposta gerada (Not Found, Bad Request, Created, etc)
- **Tarefas:**
  - Rotas relacionadas a autenticação:
    - Realizar login na aplicação
    - Criação de novo usuário no sistema
  - Produtos
    - Criação de um novo produto
    - Listagem de produtos existentes
    - Leitura de um produto específico
    - Atualização de um produto existente
    - Remoção de um produto específico
  - Clientes
    - Cadastro de um novo cliente
    - Listagem de clientes existentes
    - Leitura de um cliente específico
    - Atualização de um cliente existente
    - Remoção de um cliente específico
  - Vendas
    - Criação de uma nova venda
    - Listagem de vendas existentes

### Persistência de Dados

- Utilizar um banco de dados a sua escolha
- Poderá ser utilizado um banco de dados relacional como PostgreSQL, MySQL, etc, ou não relacional, como MongoDB
- Caso escolha um banco de dados relacional, implementar corretamente os relacionamentos propostos

### Docker e Docker Compose

- Utilizar Docker e Docker Compose para realizar a orquestração de containers da aplicação

### Git & GitHub

- Utilizar o git para versionamento de código. Publicar o desenvolvimento do teste em um repositório público no GitHub
- O repositório deve conter um arquivo README com instruções de instalação e execução do projeto

## Avaliação

O projeto será avaliado com base nos seguinte critérios:

- **Qualidade do código:** organização, clareza, boas práticas, etc. Será avaliado no geral a proeficiência com as tecnologias empregadas
- **Implementação da API:** verificar se a implementação atende as regras especificadas ou acrescenta regras novas conforme necessário que não tenham sido descritas
- **Persistência de dados:** será avaliado as decisões tomadas em relação a modelagem e persistência de dados
- **Versionamento de código:** avaliação da clareza nas mensagens de commits e separação de commits/branchs por features caso seja necessário
- **Escalabilidade:** verificar se a solução proposta está adequada para escalar com novos módulos, quantidade de usuários, novos casos de uso, etc.
- **Adaptação:** caso não consiga implementar um determinado recurso, será avaliado a solução para adaptação em relação a este recurso e quais propostas podem ser feitas para o futuro

## Materiais de Referência

- [Documentação Node.js](https://nodejs.org/en)
- [Documentação NestJS](https://nestjs.com/)
- [Documentação Express](https://expressjs.com/)
- [Documentação Docker](https://docs.docker.com/)
- [Documentação Docker Compose](https://docs.docker.com/compose/)
- [Documentação TypeORM](https://typeorm.io/)

Caso possua acesso a plataforma Alura:

- [Nest.js: Persistindo dados com TypeORM e PostgreSQL](https://cursos.alura.com.br/course/nest-js-typeorm)
- [Nest.js: criando uma API Restful](https://cursos.alura.com.br/course/nestjs-criando-api-resftul)
- [APIs com Node.js e Express](https://cursos.alura.com.br/formacao-node-js-express)
