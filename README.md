# IGNITE API TODOLIST
- Api para cadastro de tarefas
- 1º Desafio da Trilha NodeJs do programa Ignite da Rocketseat

## Features :rocket:
- Cadastro de Tarefas (POST /tasks)
- Listagem de Tarefas (GET /tasks)
- Atualização de Tarefas (PUT /tasks/id)
- Pesquisa de Tarefas (GET /tasks)
- Deleção de Tarefas (DELETE /tasks/id)

## Stacks :robot:
- Node
- CSV Parse

## Funcionamento:
- Faça o fork do projeto ou clone
- Execute o projeto com o comando: 
  ```
  npm run dev
  ```
- Utilize em qualquer ferramenta para testar APIs: Insomnia, Postman
- A aplicação está rodando na porta 3333 por padrão, então quando for testar as rotas:
  ```
  Criar Tarefas: localhost:3333/tasks (Adicione no Body o title, e a description da tasks)
  Listar Tarefas: localhost:3333/tasks
  Atualizar Tarefa: localhost:3333/tasks/id_da_tarefa (Atualize no Body o title, e a description da tasks)
  Pesquisa Tarefa: localhost:3333/tasks (Pesquise na Query pelo title da task)
  Deletar Tarefa: localhost:3333/tasks/id_da_tarefa
  ```