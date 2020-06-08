#colocar o nome de usuário e e-mail
git config --global user.name "usuario"
git config --global user.email "usuario@gmail.com"

#inicializa o git e cria o diretório do projeto
git init <projeto>

#cria um arquivo
touch <arquivo>

#cria um um ponto na história do arquivo
git add <arquivo>

#faz o commit do ponto
git commit -m "observação que pode ser adicionado ao commit"

#mostra todos os commits de um arquivo
git log <arquivo>

#mostra o status dos arquivos da pasta (o que foi modificado)
git status

