<img alt="GoStack" src="https://res.cloudinary.com/stefanosaffran/image/upload/v1586943536/d32tomvl6x8onypta01h.png" />

<h3 align="center">
  Desafio 02 - Node.js conceitos.
</h3>

<p align="center">
  <a href="#-projeto">Projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-tecnologias">Como rodar o projeto</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-agradecimentos">Agradecimentos</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

<blockquote align="center">been there, done that!</blockquote>

<p align="center">
  <a> </a>
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/IgorCastromann/Desafio04Mod01-ReactNative?color=2304D361">
  <img alt="Last commit on GitHub" src="https://img.shields.io/github/last-commit/IgorCastromann/Desafio04Mod01-ReactNative?color=2304D361">
  <img alt="Made by Igor Castro" src="https://img.shields.io/badge/made%20by-Igor Castro-%20?color=2304D361">
  <img alt="Project top programing language" src="https://img.shields.io/github/languages/top/IgorCastromann/Desafio04Mod01-ReactNative?color=2304D361">
</p>


## 💻 Projeto 

Aplicação para conectar o frond-end, em React Native, com o back-end e adicionar likes através da API nos repositórios.


## 🚀 Tecnologias

Esse projeto foi desenvolvido com as seguintes tecnologias:

- [ReactNative](https://https://reactnative.dev/)

<p> e necessário funcionando no back-end:</p>

- [Node.js](https://nodejs.org/en/)


## 🛰 Como rodar o projeto
### Pré-requisitos

Antes de começar, você vai precisar ter instalado em sua máquina as seguintes ferramentas:
[Git](https://git-scm.com), [Node.js](https://nodejs.org/en/) e [ReactNative](https://https://reactnative.dev/).
Além disto é bom ter um editor para trabalhar com o código como _VSCode_


## Rodando o Projeto - back-end

```bash
# Clone este repositório
$ git clone https://github.com/IgorCastromann/Desafio02-Mod01-GoStack

# Acesse a pasta do projeto no seu terminal/cmd
$ cd Desafio02-Mod01-GoStack

# Instale as dependências
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ yarn dev

# O servidor estará rodando na porta:3333 - http://localhost:3333
```

## Rodando o Projeto - front-end

```bash
# Clone este repositório
$ git clone https://github.com/IgorCastromann/Desafio04Mod01-ReactNative

# Acesse a pasta do projeto no seu terminal/cmd
$ cd Desafio04Mod01-ReactNative

# Instale as dependências
$ yarn

# Execute a aplicação em modo de desenvolvimento
$ yarn start
```

## Api.js


Arquivo necessário para conectar o emulador de android no back-end da aplicação
```
import axios from "axios";

const api = axios.create({
  baseURL: "http://10.0.2.2:3333",
});

export default api;
```


## 🙌 Agradecimentos

- [Time da RocketSeat](https://rocketseat.com.br/)

## :mailbox_with_mail: Get in touch!


<a href="https://www.linkedin.com/in/igor-castro-27470672/" target="_blank" >
  <img alt="Linkedin - Igor Castro" src="https://img.shields.io/badge/Linkedin--%23F8952D?style=social&logo=linkedin">
</a>&nbsp;&nbsp;&nbsp;
<a href="mailto:castromann@live.com" target="_blank" >
  <img alt="Email - Igor Castro" width="35rem" height="25rem" src="https://img2.gratispng.com/20180401/cwe/kisspng-outlook-com-microsoft-outlook-logo-microsoft-offic-outlook-5ac078594dd532.5951870815225631613188.jpg">
</a> 

---

Made with the spirit of a 🐻 by Igor Castro.
