
# Aula - Versionamento:
Aula geral sobre as funcionalidades do GitHub

## Adicionado Configurações GitHub:
--------------------------------
Testes com as funcionalidades do GitHub em um projeto.

--------------------------------
### Comandos iniciais - Com o diretório baixado do git:

Abrir o diretório e seguir com os seguintes comandos:

```sh
git add .
git commit -m "Comentando via comandos no bash do vscode. 1 - Comentados no readme"
```
* Em alguns casos é necessário alguns comandos adicionais, como:
```sh
 git config --global user.email "your@example.com"
 git config --global user.name "your Name"

```
* Agora sim, o comando "push":
```sh
git push origin main
```
________________________________

### Criando do zero o diretório e o repositório:

Criando o diretório via bash:

*Organize os diretórios para os códigos* 

```sh
mkdir nomedorepositório
cd nomedorepositório

```

Inicializar o git no novo repositório:

```sh
git init
```
Segue os mesmos comandos anteriores:

```sh
git add .
git commit -m "Meu Primeiro commit - Adicionado o README.md"
```
*Quando esse comando é executado, já cria uma brach "master", não é necessário um comando para criar nova brach "main"*

Para conectar remotamente o repositório, seguem os comandos:
```sh
 git remote add oringin https://github.com/meulogingit/meurepositorio.git

```
* Agora sim, o comando "push":
```sh
git push origin master
```
_______________________________


------------------------------------------------
##Atualizando o Status

Baixei uma solução teste para testes as funcionalidades dos comanandos.

------------------------------------------------


















































##### Autor:

*Feito com ❤️ por Eduardo 👋🏽 Entre em contato!*

[![Linkedin Badge](https://img.shields.io/badge/-Eduardo-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/eduardo-pateis-joaquim/)](https://www.linkedin.com/in/eduardo-pateis-joaquim/)
