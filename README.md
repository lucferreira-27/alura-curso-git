# alura-curso-git
Curso da alura de git
## Comandos
- git init =  inicializa o repositio
- git add (nome do arquivo)
- git commit -m ""
- git remote add [nome do reposotorio] (link/caminho) = adiciona um repositorio
- git push -u origin [branch] = "empurra" o commit para repositório 
- git checkout [branch] = troca de branch
- git branch = lista as branchs
- git merge  [branch] = realiza um merge entre branchs
-git tag -a [VERSION] = cria uma tag  com release
- git push origin [VERSION] = envia a versão para um servidor remoto.
## CTRL + Z

- Para desfazer uma alteração antes de adicioná-la para commit (com git add), podemos utilizar o comando git checkout -- <arquivos>.

- Para desfazer uma alteração após adicioná-la para commit, antes precisamos executar o git reset HEAD <arquivos> e depois podemos desfazê-las com git checkout -- <arquivos>.

- Para revertermos as alterações realizadas em um commit, o comando git revert pode ser a solução.



## help
https://git-school.github.io/visualizing-git/
