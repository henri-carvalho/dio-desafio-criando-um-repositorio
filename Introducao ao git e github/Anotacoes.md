##criando chave ssh

$ ssh-keygen -t ed25519 -C "your_email@example.com"

## start the ssh-agent in the background

$ eval "$(ssh-agent -s)"

## adicionar a chave aos dispoositivos confiaveis

$ ssh-add ~/.ssh/id_ed25519

##alterar dados da sua chave 

$ git config --global user.name "user name"

$ git config --global user.email johndoe@example.com

##Status do repositório

$ git status

##criar novo repositório

$ git init

##adicionar ao repositorio

$ git add 

##commitar alteração

$git commit

## puxar a versao mais recente

$ git pull

## empurrar para o github

git push
