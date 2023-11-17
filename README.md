# Vue Todo App

Este é um aplicativo simples em Vue.js para gerenciar uma lista de tarefas. Ele permite aos usuários adicionar e remover tarefas categorizadas como negócios ou pessoais.

## Recursos

- Adicionar novas tarefas com uma descrição e categoria.
- Marcar tarefas como concluídas.
- Remover tarefas da lista.

## Tecnologias Utilizadas

- Vue.js

## Instruções de Configuração

1. Clone o repositório.
2. Instale as dependências utilizando `npm install`.
3. Execute o aplicativo usando `npm run dev`.

## Visão Geral do Código

O código está estruturado da seguinte forma:

### Estrutura do Componente Vue

- **Script Setup**: Inicializa o componente Vue e gerencia as funcionalidades da lista de tarefas.
- **Template**: Define a estrutura da interface com seções para cumprimento, criação de tarefas e exibição da lista de tarefas.

### Script Setup

- Importa funções e recursos necessários do Vue.
- Inicializa variáveis reativas para gerenciar tarefas, valores de entrada e nome do usuário.
- Utiliza observadores (watchers) e ganchos do ciclo de vida (`onMounted`) para gerenciar o armazenamento local e atualizar dados.
- Define métodos para adicionar e remover tarefas.

### Template

- Seção de Cumprimento: Permite aos usuários inserir seu nome.
- Seção Criar Tarefa: Formulário para adicionar novas tarefas com campos para conteúdo e seleção de categoria.
- Seção Lista de Tarefas: Exibe a lista de tarefas com caixas de seleção para conclusão, conteúdo editável e botão de exclusão.

## Uso

1. Insira seu nome no campo fornecido para personalizar a saudação.
2. Preencha o conteúdo da tarefa e selecione uma categoria, depois clique em "Adicionar tarefa" para adicionar uma nova tarefa.
3. Visualize a lista de tarefas e marque as tarefas como concluídas marcando as caixas de seleção.
4. Para remover uma tarefa, clique no botão "Excluir" associado a essa tarefa.

## Armazenamento Local

- O nome do usuário e os dados da lista de tarefas são armazenados no armazenamento local do navegador.
- O nome do usuário persiste entre sessões.
- Os dados da lista de tarefas persistem e são carregados ao atualizar a página.


---

# English

# Vue Todo App

This is a simple Vue.js application for managing a todo list. It allows users to add and remove tasks categorized as business or personal.

## Features

- Add new tasks with a description and category.
- Mark tasks as completed.
- Remove tasks from the list.

## Technologies Used

- Vue.js

## Setup Instructions

1. Clone the repository.
2. Install dependencies using `npm install`.
3. Run the application using `npm run dev`.

## Code Overview

The code is structured as follows:

### Vue Component Structure

- **Script Setup**: Initializes the Vue component and manages the todo list functionalities.
- **Template**: Defines the UI structure with sections for greeting, creating todos, and displaying the todo list.

### Script Setup

- Imports necessary functions and features from Vue.
- Initializes reactive variables for managing todos, input values, and user name.
- Utilizes watchers and lifecycle hooks (`onMounted`) for managing local storage and updating data.
- Defines methods for adding and removing todos.

### Template

- Greeting Section: Allows users to input their name.
- Create Todo Section: Form for adding new todos with fields for content and category selection.
- Todo List Section: Displays the list of todos with checkboxes for completion, editable content, and delete button.

## Usage

1. Enter your name in the provided input field to personalize the greeting.
2. Fill in the todo content and select a category, then click "Add todo" to add a new task.
3. View the todo list and mark tasks as completed by checking the checkboxes.
4. To remove a task, click the "Delete" button associated with that task.

## Local Storage

- User's name and todo list data are stored in the browser's local storage.
- The user's name persists across sessions.
- Todo list data persists and loads on page refresh.