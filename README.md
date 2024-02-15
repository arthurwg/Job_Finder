# Job_Finder
Aplicação em node para procurar e criar vagas de emprego.

Este é um projeto Node.js que oferece funcionalidades para buscar vagas de trabalho por texto e criar novas vagas através de um formulário.

![Imagem da aplicação](https://imgur.com/X0JjBRs)

![Vagas](https://imgur.com/j5x3qKh)



## Configuração do Banco de Dados

O projeto utiliza SQLite como banco de dados. O arquivo do banco de dados está localizado em `./db/app.db`.

## Instruções de Uso

Siga as etapas abaixo para utilizar o projeto:

### Pré-requisitos

- Node.js instalado no seu sistema
- Dependências do projeto instaladas (execute `npm install` no diretório do projeto)
- Banco de dados SQLite configurado (o arquivo `app.db` será criado automaticamente na pasta `./db/`)

### Configuração do Banco de Dados

O projeto utiliza SQLite como banco de dados. Certifique-se de que o banco de dados está configurado corretamente e o arquivo `app.db` está presente na pasta `./db/`.

### Iniciar o Servidor

Para iniciar o servidor, execute o seguinte comando no terminal:


Claro, aqui está o README.md revisado com base nas informações fornecidas:

markdown
Copy code
# Projeto Node.js de Busca de Vagas de Trabalho

Este é um projeto Node.js que oferece funcionalidades para buscar vagas de trabalho por texto e criar novas vagas através de um formulário.

## Configuração do Banco de Dados

O projeto utiliza SQLite como banco de dados. O arquivo do banco de dados está localizado em `./db/app.db`.

## Instruções de Uso

Siga as etapas abaixo para utilizar o projeto:

### Pré-requisitos

- Node.js instalado no seu sistema
- Dependências do projeto instaladas (execute `npm install` no diretório do projeto)
- Banco de dados SQLite configurado (o arquivo `app.db` será criado automaticamente na pasta `./db/`)

### Configuração do Banco de Dados

O projeto utiliza SQLite como banco de dados. Certifique-se de que o banco de dados está configurado corretamente e o arquivo `app.db` está presente na pasta `./db/`.

### Iniciar o Servidor

Para iniciar o servidor, execute o seguinte comando no terminal:
```bash
npm start
```

Isso iniciará o servidor Node.js na porta padrão 3000.

### Utilizando a Aplicação

#### Buscar Vagas de Trabalho

Para buscar vagas de trabalho por texto, acesse o navegador e navegue até `http://localhost:3000/`. Você verá uma lista de todas as vagas disponíveis. Você pode usar a barra de pesquisa para filtrar as vagas por texto.

#### Criar Nova Vaga de Trabalho

Para criar uma nova vaga de trabalho, acesse o navegador e navegue até `http://localhost:3000/jobs/new`. Preencha o formulário com os detalhes da vaga e clique em "Submit" para criar a vaga.

## Funcionalidades

- Busca de vagas de trabalho por texto
- Criação de novas vagas de trabalho através de um formulário

## Tecnologias Utilizadas

- Node.js
- Express.js
- Sequelize (ORM para interagir com o banco de dados)
- Handlebars (para renderização de templates)
- SQLite (banco de dados utilizado)
