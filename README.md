# GIT E GITHUB
https://www.youtube.com/watch?v=2alg7MQ6_sI

## Para iniciar o repositorio do projeto no git
git init

## para adionar um arquivo no git(coloca o arquivo em observacao no git)
git add nomedoarquivo.extensão

## para concluir a inclusão do arquivo no git
git commit -m "Descricão do commit"

## para visualizar os pontos na historia de
git log

## mostra o status do git
git status

## para atualizar um arquivo no git
git add nomedoarquivo.extensão
## depois tem commit novamente
git commit -m "Descricão do commit"

## para exibir um ponto da historica especifica esse numero eu adquiro no git log
git show 997be9399c5c66effd75d41c6ef202de4a53a8b5

## Mostra a ultima modificacao
git show

## Branches
git branch feature/cart

## Muda de time line
git checkout feature/cart

## ver todas as linhas do tempo 
git branch

## unir as time line
### no git master
git merge nomedabranch

## deletar a branch
git branch -D nomedabranch


### github repositorio

## adicionando o repositrio remoto depois que criou o repostiro no github
git remote add origin https://github.com/FlavioViana-Dev/GitCommand.git

## sob atualização 
git push -u origin master
### depois posso usar apenas
git push 

## para adicionar todas alteracoes
git add .

## para salvar o usuario senha do github
git config credential.helper store