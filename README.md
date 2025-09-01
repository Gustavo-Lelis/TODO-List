# 📝 ToDo CLI em Go

Uma aplicação de **linha de comando (CLI)** para gerenciar tarefas, desenvolvida em **Go**.  
O objetivo do projeto é fins de **aprendizado** e prática de boas práticas com Go.

---

## 🚀 Funcionalidades

- Adicionar uma nova task
- Editar uma task existente
- Deletar uma task pelo ID
- Atualizar o status de uma task
- Listar todas as tasks cadastradas
- Persistência simples em arquivo JSON

---

## 📂 Estrutura do Projeto

TODO/
│── cmd/
│ └── myapp/
│ ├── todo.go # Arquivo principal (CLI)
│ └── todos.json # Banco de dados simples em JSON
│
│── internal/
│ ├── comandos/
│ │ └── cli_comandos.go # Flags e comandos da CLI
│ ├── repositorio/
│ │ └── bd.go # Acesso ao "banco" JSON
│ └── task_do/
│ ├── task.go # Estrutura e lógica da Task
│ └── task_test.go # Testes unitários
│
├── go.mod
├── go.work
