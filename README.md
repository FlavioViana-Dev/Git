# GIT E GITHUB
https://www.youtube.com/watch?v=2alg7MQ6_sI

## Iniciar um novo repositório no GIT
git init

## Adicionar um arquivo no GIT
git add nomedoarquivo.extensão

## Concluir a inclusão do arquivo no GIT
git commit -m "Descricão do commit"

## Visualizar os pontos na historia
git log

## Exibir o status do GIT
git status

## Atualizar um arquivo no git
git add nomedoarquivo.extensão

## Concluir a alteração
git commit -m "Descricão do commit"

## Comando curto para o commit
git commit -am "descricao"

## Exibir um ponto especifico na historia. Usar o identificador gerado no log
git show 997be9399c5c66effd75d41c6ef202de4a53a8b5

## Exibir a ultima modificacao
git show

## Branches
git branch feature/cart

## Muda de time line
git checkout feature/cart
git checkout --

## Ver todas as linhas do tempo 
git branch

## unir as time line
### no git master
git merge nomedabranch

## deletar a branch
git branch -D nomedabranch

## adicionar nova branch
git checkout -b MinhaNovaBrach
Depois, quando quiser subir a branch, faça os commits:

git commit -m 'Comentário do commit da minha nova branch'
Depois, subindo de fato:

git push --set-upstream origin MinhaNovaBrach

## Adicionar todas as alteracoes
git add .

<HR>

# GITHUB REPOSITORIO

## Conectar o repositorio local(GIT) com o repositorio remoto(GITHUB). O repostiro deve ser criado antes no GITHUB
git remote add origin https://github.com/FlavioViana-Dev/GitCommand.git

## Atualizar o GITHUB 
git push -u origin master

### Atualizar o GITHUB 
git push 

## Salvar o usuario senha do GITHUB
git config credential.helper store

## Recuperar um projeto já criado do GITHUB
git clone "https://github.com/flavio/projeto"

## Baixar atualização no servidor GITHUB
git pull
