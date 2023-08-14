# **Projeto Labeddit Back End**

📖 Introdução

O Labeddit Project consiste em uma API de publicações, na qual os utilizadores podem estabelecer uma conta, realizar o login, gerar publicações e interagir com estas através da atribuição de curtidas e comentários. Adicionalmente, o projeto desempenha um papel fundamental como alicerce para a interface do utilizador, que é concretizada no software.

As temáticas fundamentais a serem exploradas englobam:

Os principais tópicos a serem estudados incluem:

Conceitos de TypeScript.
Criação de uma API.
Implementação dos principais métodos: GET, POST, PUT e DELETE.
Arquitetura em camadas.
Programação Orientada a Objetos.
Autenticação.

## 🔗Link de Acesso

- Para ter acesso a documentação da API acesse o link: [Postman](https://documenter.getpostman.com/view/26335727/2s9Xy6ooyD)


## 📄Concepção do Projeto

### Instalando

```bash
# Instalando dependências
npm install

# executando o projeto
npm run dev e npm run start.

```

### Funcionalidades

```bash
. Requisições:
-SignUp: criar um usuario na API com o método post.
-Login: Entrar com usuário na API com o método post.
-GetPosts: Chamar todos os posts da API, mas só se informar o token criado no login ou
signup, com o método get.
-GetPostById: Chama o post com o id informado, mas só se informar o token criado no login ou
signup, com o método get.
-CreatePost: Pode criar um post na API, mas só se informar o token criado no login ou
signup, com o método post.
-CreateComment: Pode criar um comentário na API, mas só se informar o token criado no login ou
signup, com o método post.
-LikeOrDislikePost - Mecânica de like ou dislike do post da API, mas só se for informado o token
adquirido no login ou signup e o id do post a ser curtido, também será necessário informar
no body o true ou false, onde true é like e false deslike.
-LikeOrDislikeComment - Mecânica de like ou dislike do comentário da API, mas só se for informado o token
adquirido no login ou signup e o id do comentário a ser curtido, também será necessário informar
no body o true ou false, onde true é like e false deslike.
```

### Bibliotecas Utilizadas

```bash
#dependencies:
bcryptjs,
cors,
dotenv,
express,
jsonwebtoken,
knex,
sqlite3,
uuid,
zod

#devDependencies:
@types/bcryptjs,
@types/cors,
@types/express,
@types/jsonwebtoken,
@types/knex,
@types/node,
@types/uuid,
ts-node-dev,
typescript

```

## 💡Programas utilizados:

- VSCode
- PostMan

## 💻Tecnologias

![TypesScript](https://img.shields.io/badge/TypeScript-1572B6?style=for-the-badge&logo=typescript&logoColor=white)
![Express](https://img.shields.io/badge/Express-f8f8ff?style=for-the-badge&logo=express&logoColor=black)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)

