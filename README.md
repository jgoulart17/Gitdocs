leiame

Alguns comandos no git para resetar altercoes
git reset 
--soft = volta anterior para ser comitado novamente.

--mixed = volta para ser adicionado e comitado novamente.

--reset = volta tudo sem deixar rastro.

git add (arq) ou -A -> git commit -m "Message"

git branch (nome) para criar

git checkout (nome) para alterar de branch

git branch -d (name) delete branch

git diff mostra oque foi alterado no arquivo

git diff --name-only = somente nome do arquivo modificado

após termina todo o processo localmente e caso queira enviar para o seu repositório basta utilizar o comando
git push -u origin master = para subir pela primeira vez.
git push origin master = para subir alteraçoes comuns

Utilizando o .gitignore voce consegue esconder arquivos que voce nao deseja que subam para o repositorio remoto.
basta criar o arquivo e inserir dentro dele nomes, diretorios ou somente extensoes que devem ser ignoradas.
