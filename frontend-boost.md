# Desafio Frontend Boost

O desafio Frontend Boost consiste em construir uma aplicação para a web com React para consumir uma API de gerenciamento de uma loja.

A aplicação deve conter roteamento, autenticação e consumo de API. Considerar que o sistema é semelhante a um e-commerce, com vitrine de produtos, login de usuário, construção de carrinho e perfil de usuário autenticado

## Requisitos

### Frontend

- **Framework:** utilizar React como framework para composição da página e TypeScript para escrita do código
- **Estilização:** realizar a estilização CSS da página utilizando TailwindCSS. Caso tenha domínio, poderá acrescentar uma biblioteca de componentes a sua escolha como Shadcn/UI, Material ou Chakra UI, etc
- **Responsividade:** implementar a construção da página considerando a responsividade em mente
- **Roteamento:** para este projeto, construir a página utilizando o React Router para roteamento
- **Componentização:** realizar a correta separação de elementos reutilizáveis da página em seus respectivos arquivos de componentes
- **Server Side Rendering:** SSR não é um requisito do projeto, no entanto, caso deseje, poderá utilizar um framework como Next.js para construção da página
- **Formulários**: para construção dos formulários, utilizar a ferramenta React Hook Form

### Consumo de API e Persistência de Dados

- Para este projeto, não será considerado persistência de dados locais, e sim, consumo de dados existentes em uma API de testes
- No entanto, a API não cria recursos reais (verificar a documentação), então algumas etapas, como a criação de carrinho poderá ser feita localmente
- A API disponibilizada é a seguinte: [Fake Store API](https://fakestoreapi.com/)
- Poderá utilizar a ferramenta nativa Fetch ou bibliotecas como Axios para realizar o consumo da API

### Autenticação

- Neste projeto, considerar a existência de rotas privadas, que só poderão ser acessadas após realizar o login, como por exemplo um perfil de usuário
- Criar corretamente os contextos necessários para esse recurso
- Utilizar a ferramenta nativa de contexto do React, porém, caso deseje, poderá utilizar alguma outra biblioteca de gerenciamento de contexto que possua domínio

### Git & GitHub

- Utilizar o git para versionamento de código. Publicar o desenvolvimento do teste em um repositório público no GitHub
- O repositório deve conter um arquivo README com instruções de instalação e execução do projeto

## Avaliação

O projeto será avaliado com base nos seguinte critérios:

- **Qualidade do código:** organização, clareza, boas práticas, etc. Será avaliado no geral a proeficiência com as tecnologias empregadas
- **Versionamento de código:** avaliação da clareza nas mensagens de commits e separação de commits/branchs por features caso seja necessário
- **Criatividade e estilo:** será avaliado a habilidade de estilização e composição das telas e elementos de UI
- **Responsividade:** a maneira como a página construída se comporta em dispositivos de diferentes tamanhos de tela, web e mobile, também será avaliada
- **Escalabilidade:** verificar se a solução proposta está adequada para escalar com novos módulos, quantidade de usuários, novos casos de uso, etc.
- **Adaptação:** caso não consiga implementar um determinado recurso, será avaliado a solução para adaptação em relação a este recurso e quais propostas podem ser feitas para o futuro

## Materiais de Referência

- [Documentação React](https://react.dev/)
- [Documentação TailwindCSS](https://tailwindcss.com/)
- [Documentação React Hook Form](https://www.react-hook-form.com/)
- [Documentação Next.js](https://nextjs.org/)
- [Documentação Fetch](https://developer.mozilla.org/pt-BR/docs/Web/API/Fetch_API/Using_Fetch)
- [Documentação Axios](https://axios-http.com/docs/intro)

Caso possua acesso a plataforma Alura:

- [React: desenvolvendo com JavaScript](https://www.alura.com.br/curso-online-react-desenvolvendo-javascript)
- [Tailwind CSS: estilizando a sua página com classes utilitárias](https://www.alura.com.br/curso-online-tailwind-css-estilizando-pagina-classes-utilitarias)
- [React: conhecendo a biblioteca React Router](https://cursos.alura.com.br/course/react-biblioteca-react-router)
- [React: integrando seu projeto React com APIs](https://cursos.alura.com.br/course/react-integrando-projeto-react-apis)
- [React: autenticando usuários](https://cursos.alura.com.br/course/react-autenticando-usuarios)
