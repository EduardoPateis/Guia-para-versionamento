
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
##Atualizando

#### Observação:

  *Baixei uma solução $"teste"$ para os testes das funcionalidades dos comanandos pra o Github.*



1 - Consultar o status:

```sh
git status
```
2 - Adicionar todos os novos arquivos e diretórios:

```sh
git add .
```
3 - Adicionar os comentários da edição, "commit":

```sh
git commit -m "Aqui seus comentários da edição"
```
4 - Atualizar o repositório local com as alterações recentes do repositório remoto.

```sh
git put origin "nome da Branch"
```
* 4.1 - Para consultar o branch:

```sh
git branch
```
5 - Enviar as modificações realizadas em um repósitorio local para um resosiório remoto:

```sh
git push
```

6 - Verifica o status de versionamento entre o remoto e o local:

```sh
git log
```
* 6.1 - Comandos adicionais para o comando "log":
--oneline - resume a exibição do commit em uma linha simplificada.
--stat - exibe uma estatítica de quais arquivos foram alterados e a quantidade de linhas alteradas de maneira bem simplificada.
--author="nome" - irá destacar e exibir apenas os logs relacionados ao autor.
--grep="texto" - irá exibir uma pesquisa nos commints texto solictido.

7 - Checkout navega entre os comnits ou branches.
```sh
git checkout "codigo do commit ou o nome do branch"
```

$teste:$ 

Solução de front end de um e-commerce.

------------------------------------------------


















































## Autor:

*Feito com ❤️ por Eduardo 👋🏽 Entre em contato!*

[![Linkedin Badge](https://img.shields.io/badge/-Eduardo-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/eduardo-pateis-joaquim/)](https://www.linkedin.com/in/eduardo-pateis-joaquim/)
