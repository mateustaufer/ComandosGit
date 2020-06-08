#colocar o nome de usuário e e-mail
git config --global user.name "usuario"
git config --global user.email "usuario@gmail.com"

#inicializa a linha do tempo do projeto
git init <projeto>

#cria um arquivo
touch <arquivo>

#adiciona ou atualiza mudanças que irão para linha do tempo de um arquivo
git add <arquivo>

#restaura o arquivo com a última versão que está no git
git restore <arquivo>

#adiciona o que foi alterado na linha do tempo
git commit <arquivo> -m "observação que pode ser adicionado ao commit"

#mostra todos os commits de um arquivo (se não usar o nome do arquivo ele traz o log de todos os arquivos do diretório)
git log <arquivo>

#mostra o status do arquivo (ou do diretório se não houver <arquivo> no comando)
git status <arquivo>

#mostra o que foi modificado no commit (ou no último commit caso não tenha o número do commit)
git show <numero do commit>

#cria uma nova branch <branch> (se não usar o <branch> ele mostra árvore de branchs do projeto)
git branch <branch>

#troca para a branch <branch>
git checkout <branch>

#manda as modificações de um branch <branch> para o branch que está checkado
git merge <branch>

#deletar a branch
git branch -D <branch>

#mandar para o GitHub
git remote add origin https://github.com/mateustaufer/<repositorio>.git

#mostrar os repositorios remotos
git remote -v

#enviar o projeto pro repositorio pela primeira vez
git push -u origin master