# Job_Finder
Aplicação em node para procurar e criar vagas de emprego.

Este é um projeto Node.js que oferece funcionalidades para buscar vagas de trabalho por texto e criar novas vagas através de um formulário.

![Imagem da aplicação](https://i.imgur.com/X0JjBRs.png)

![Vagas](https://i.imgur.com/j5x3qKh.png)

## Como Obter o Projeto

Para obter o projeto em seu ambiente local, você pode seguir estas etapas:

### Clonar o Repositório

1. Abra o terminal ou prompt de comando.
2. Navegue até o diretório onde deseja armazenar o projeto.
3. Execute o seguinte comando para clonar o repositório:

```bash
git clone https://github.com/arthurwg/Job_Finder.git
```

ou baixe o arquivo .zip.



## Instruções de Uso

Siga as etapas abaixo para utilizar o projeto:

### Pré-requisitos

- Node.js instalado no seu sistema
- Dependências do projeto instaladas (execute `npm install` no diretório do projeto)
- Banco de dados SQLite configurado (o arquivo `app.db` será criado automaticamente na pasta `./db/`)

## Configuração do Banco de Dados

O projeto utiliza SQLite como banco de dados. O arquivo do banco de dados está localizado em `./db/app.db`.

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
