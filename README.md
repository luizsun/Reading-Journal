# Nome: LUIZ GUSTAVO SIQUEIRA SUN


## Para executar o projeto:
### 1. Entrar na pasta do projeto no terminal
```sh
cd reactjs/reading-journal
```

### 2. Instalar dependências
Rode npm install para instalar as dependências do projeto:
```sh
npm install
```

### 3. Rodar a aplicação
Rode npm start, para iniciar a execução do projeto.
```sh
npm start
```
Acesse a aplicação no navegador em `http://localhost:3000/`.


## Introdução
Este projeto faz parte da disciplina **Desenvolvimento de Sistemas Front-end** e tem como objetivo implementar um CRUD para um **Reading Journal**. A aplicação permite **cadastrar, listar, editar e excluir livros**.

## Estrutura do Projeto
A estrutura de arquivos está organizada da seguinte maneira:
```
📦 src/
 ┣ 📂 components/
 ┃ ┣ 📂 NavBar/ → Componente de navegação
 ┃ ┣ 📂 BookForm/ → Formulário para adicionar e editar livros
 ┃ ┗ 📂 BookList/ → Lista de livros cadastrados, com opção de edição e exclusão
 ┣ 📜 App.js → Componente principal da aplicação
 ┗ 📜 index.js → Arquivo de inicialização
```

## Componentes
### **1 - NavBar**
Componente responsável pela navegação entre as páginas.
- Exibe links para **Página Inicial, Sobre, Cadastro e Lista de Livros**.
- Utiliza `react-router-dom` para gerenciar a navegação.

### **2 - BookForm**
Componente que contém o formulário para **cadastrar e editar livros**.
- Campos obrigatórios: **Título, Autor, Gênero e Ano**.
- Validação para impedir envio de campos vazios.
- Se estiver editando um livro, os campos já vêm preenchidos.

### **3 - BookList**
Componente que exibe a **lista de livros cadastrados**.
- Cada livro possui opções de **editar e excluir**.
- A listagem é recebida como `props` do `App.js`.

## Prints da Aplicação
### Página Inicial
![Página Inicial](./prints-resultados/home.png)
### Página Sobre
![Página Sobre](./prints-resultados/sobre.png)
### Página de Cadastro
![Página de Cadastro](./prints-resultados/cadastrar.png)
### Página de Cadastro, adicionando livro.
![Página de Cadastro add livro](./prints-resultados/adicionar.png)
### Lista de Livros
![Lista de Livros](./prints-resultados/lista.png)
### Editar um livro
![Editar Livro](./prints-resultados/editar.png)
### Excluir um livro
![Excluir Livro](./prints-resultados/excluir.png)

## Conclusão
Este projeto demonstra a implementação de um CRUD básico em React, explorando a componentização e o uso do `react-router-dom`.

---
Desenvolvido por **[Luiz Gustavo Siqueira Sun]** para a disciplina Desenvolvimento de Sistemas Front-end, Análise e Desenvolvimento de Sistemas - PUC-RS.


