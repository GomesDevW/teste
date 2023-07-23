
git --all - Mostra de maneira visual os commits e branches do repositório

git remote add origin "link" - vincular o repositório local com o remoto
ou
git clone "link do repositorio" - Clona um repositório 

git init - Criar o repositório

git status - Verifica se há alguma alteração não trackeada
tree 
git log - Histórico de alterações

git commit -am ""descrição entre aspas"" - Enviar para o repositório e branch

git branch nome do branch - Criar branch

git checkout -b "nome" - Criar uam branch e ir para ela

git branch - Verifica em qual branch vc está

git checkout "nome do branch ou master" - Alternar entre os branchs

git checkout HEAD "nome do arquivo.extensão" - Esquece todas as alterações realizadas e não commitadas e volta pra versão anterior

git add -A - Adiciona todos os itens pendentes de trackeamento

git add "nome do arquivo "- Adiciona um arquivo específico

git reset --soft - Volta para o estado antes do commit, sem alterar os códigos

git reset --mixed - Mesma coisa que o soft, só que vai ter que dar o ADD de novo

git reset --hard - Retorna para o estado escolhido, retirando as modificações realizadas

tree /f - mostra uma árvore dos arquvios que contém na pasta

cd .. - Volta uma pasta

git diff - Visualiza o que foi alterado no arquivo

git diff --name-only - Mostra em quais aquivos houveram alterações 

git diff "nome do arquivo.extensão"  - Mostra as modificações de um arquivo específico

git push -u origin master - mandar para o repositorio remoto (o -u só coloca da primeira vez)

git revert --no-edit "codigo do commit" - reverte alterações realizadas e commitadas e commita de novo.

git push origin :"nome do branch" - remover um branch remoto

git branch -D "nome do branch" - remover um branch local



git merge "nome da branch" - mescla a branch escolhida com a branch atual

git remote -v - Vê qual o nome do repositório

Para contribuir com um projeito no github, devemos clicar em "FORK" para clonar o repositório automaticamente para o seu perfil do github. Após isso, damos um pull para trabalhar no repositório local, realizamos as alterações, dps damos push para atualizar o repositório remoto. Depois podemos ir fazer o new pull request e enviar as modificações para o dono.


Obs.: É recomendado dar um pull no repositório remoto antes de dar um push para o repositório remoto. Assim, garante que você mandou os arquivos mais atualizados