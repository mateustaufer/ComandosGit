#colocar o nome de usuário e e-mail
git config --global user.name "usuario"
git config --global user.email "usuario@gmail.com"

#inicializa o git e cria o diretório do projeto
git init <projeto>

#cria um arquivo
touch <arquivo>

#adiciona as alterações no ponto da história do arquivo
git add <arquivo>

#faz o commit do ponto
git commit -m "observação que pode ser adicionado ao commit"

#mostra todos os commits de um arquivo (se não usar o nome do arquivo ele traz o log de todos os arquivos do diretório)
git log <arquivo>

#mostra o status dos arquivos da pasta (o que foi modificado)
git status