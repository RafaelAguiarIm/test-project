# test-project
Apenas um teste dos comandos do Git


Revisando comandos do git

<h1> Comando Básicos do Git </h1>
git --help - Ajuda 

git init  - criação da pasta.git
git add "nome do arquivo" - Adiciona arquivo um a um
Git add . - adiciona todos os arquivops de uma vez
git comit -m "Descrição do que esta sendo comitado" - comando para realizar o comit

Configuração do Usuário CL
git config --global user.email "email"
git config --global user.name "nome"

Enviando a primeira versão dos codigos para o servidor
git remote add origin link do repositorio - comando para vincular o projeto da máquina com o do github
git push - empurrar o arquivo para o github (Só funciona se o branch estiver definido
git push --set-upstream origin master - push definindo qual branch usar, neste ex foi usado a master
