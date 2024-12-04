# Desafio Backend Start

O desafio Backend Start consiste em criar um sistema de tarefas do tipo To-Do List.

O sistema deve ser implementado como uma API, com endpoints para gerenciamento das tarefas.

Para este projeto, não é necessário considerar persistência de dados ou autenticação.

## Requisitos

### Backend

- **Linguagem de programação:** Utilize a linguagem JavaScript através do runtime Node.js, caso deseje, poderá utilizar TypeScript para desenvolvimento do código
- **Framework:** Se desejar ou conhecer, pode utilizar o NestJS para desenvolvimento da API de backend, caso contrário, desenvolver utilizando Node.js e Express
- **Arquitetura:** seguir uma arquitetura baseada em módulos, contendo controllers, services e repositórios
- **Tarefas:**
  - Rotas relacionada ao gerenciamento de tarefas:
    - Criar uma nova tarefa
    - Listar tarefas existentes
    - Ler um tarefa específica
    - Atualizar um tarefa existente
    - Marcar uma tarefa como finalizada
    - Remover uma tarefa existente
  - Modelagem da tarefa:
    - Título
    - Descrição
    - Status
    - Data de criação
    - Data de atualização

### Persistência de Dados

- Para este projeto, não é necessário realizar a persistência de dados, os dados podem ser salvos localmente em memória
- Uma possível solução seguindo o modelo de "repositórios" seria criar um repositório "virtual" apenas em memória
- Modelar corretamente as "entidades" que solucionam os problemas propostos
- Acrescentar especificações que julgar necessárias caso não tenham sido informadas

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

Caso possua acesso a plataforma Alura:

- [Nest.js: criando uma API Restful](https://cursos.alura.com.br/course/nestjs-criando-api-resftul)
- [APIs com Node.js e Express](https://cursos.alura.com.br/formacao-node-js-express)
