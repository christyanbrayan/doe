# ![DOE logo](public/logo.png "logo DOE")
## Um sistema de cadastro de doadores de sangue
### Aplicação web criada a partir da 3ª MaratonaDev da Rocketseat, evento online ocorrido gratuitamente durante os dias 17 e 18 de Fevereiro de 2020
### Instrutor: [Mayk Brito](https://github.com/maykbrito)
![Rocketseat](rocketseat.png "rocketseat.com.br")
## Tecnologias
### Front-end
- **HTML5**
- **CSS3**
- **JS**
### Back-end
- **JS**
- **Servidor Node.js**
  - Com as dependências **Express, Nodemon e Nunjucks**
- **Banco de Dados Postgres**

## Dependências

Instaladas através do npm, o **express** (para o servidor web), o **nodemon** (para escutar os arquivos e diretórios, sem precisar reiniciar o nodejs a cada alteração) e o **nunjucks** (para organizar e manipular os conteúdos HTML de forma dinâmica, através de templates engines).

### Banco de dados Postgres
Ligação através do cliente PostgreSQL para node.

`npm install pg`

Foi criado um banco chamado "**doe**", com uma tabela "**donors**" e com as linhas **id**, **name**, **email** e **blood**.

## Para rodar a aplicação

`npm start`

O terminal deve retornar: "Servidor iniciado."

Acesso via **localhost:3000**

## Interface

Visualização inicial da página
![print1](prints/print1.png "Visualização da página")

---

Ao clicar no botão
![print2](prints/print2.png "Ao clicar em quero ajudar")

---

Cadastramento de um novo doador e visualização na lista de últimos doadores
![print3](prints/print3.png "Adicionando um novo doador, que é adicionado na lista em baixo")

---

Visualização no postbird dos doadores cadastrados no banco de dados postgres
![print4](prints/print4.png "Visualização dos doadores cadastrados no banco de dados através do Postbird")

## Licença
[MIT](https://github.com/christyanbrayan/doe/blob/master/LICENSE)
