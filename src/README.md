# Ignite - Desafio 01 - Conceitos Node.js

Essa será uma aplicação para gerenciar tarefas (em inglês *todos*). Será permitida a criação de um usuário com `name` e `username`, bem como fazer o CRUD de *todos*:

- Criar um novo *todo*;
- Listar todos os *todos*;
- Alterar o `title` e `deadline` de um *todo* existente;
- Marcar um *todo* como feito;
- Excluir um *todo*;

Tudo isso para cada usuário em específico (o `username` será passado pelo header). A seguir veremos com mais detalhes o que e como precisa ser feito 🚀


## Especificação dos Testes

- [x] Deve ser possível criar um novo usuário

- [x] Não deve ser possível criar um novo usuário com nome de usuário já existente

- [x] Deve ser possível listar todas as tarefas de um usuário.

- [x] Deve ser possível criar uma nova tarefa

- [x] Deve ser possível atualizar uma tarefa

- [x] Não deve ser possível atualizar uma tarefa inexistente

- [x] Deve ser possível marcar uma tarefa como realizada

- [x] Não deve ser possível marcar uma tarefa inexistente como realizada

- [x] Deve ser possível excluir uma tarefa

- [x] Não deve ser possível excluir uma tarefa inexistente


## Executando a aplicação

- Após clonar o repositório, navegue até o diretório pelo terminal e execute o comando `yarn` para instalar todas as dependências.

- Execute o comando `yarn dev` para rodar a aplicação em modo de desenvolvimento

- Execute o comando `yarn test` para rodar os testes.