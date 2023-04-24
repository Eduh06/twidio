# Twidio

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=Finalizado&color=RED&style=for-the-badge)



## Aplicação desenvolvida através do curso Formação Quality Assurance (QA) Experience para mostrar os princípios do TDD com Node e TS.


Este projeto usa
- Node
- Typescript
- Jest
- SQLite
- TypeORM


### Como rodar o projeto

1 - Clone o repositório


2 - Instale todas as dependências

- yarn install


3 - Acesse a rota principal

http://localhost:5000/v1/

## Testando o projeto

### Testes unitários

- yarn test:unit


### Testes de integração
1 - Rode a aplicação em modo de desenvolvimento

- yarn run dev


### Rode os testes de integração no repositório /tests

- yarn test:integration

## endpoints


### GET /posts

Retorna todos os posts criados no banco de dados

- Exemplo : http://localhost:5000/v1/posts


## POST /posts (em desenvolvimento)

- Cria um novo post no banco de dados. Todos os campos são obrigatórios

Exemplo :

body {
    author: 'author@email.com',
    content: 'Tuite de exemplo'
}

