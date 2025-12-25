# Git-GH1
Repo teste para Git&amp;Github

# comandos interessantes:
- git init
- git remote -v
- git remote add/rm origin
- git status
- git add . -> adiciona modificação para ser trackeada
- git restore . -> descarta alteração
- git commit -a -m "mensagem"
- git push
- git push --set-upstream origin nome_da_branch
- git pull
- git clone https://... .
- git log
- git branch
- git branch -b nova_branch
- git checkout 
- git stash
- git tag
- git tag -a nome -m "descrição"
- git fetch -a ->adiciona branch
- git submodule
- git submodule add https://... name
- git push --recurse-submodule=on-demand
- git clean -> limpa arquivos antes de serem added, bom para quando n foi adicionado um gitignore bem feito.
- git clean -f -> força a limpeza

# comandos de rotina

- git gc -> libera memória retirando arquivos que o git julga desnecessários
- git fsck -> Verifica a integridade de arquivos

# Comandos expecíficos

- git reflog -> descreve cada ação do repo
- git reset --hard hash -> retorna ao ponto exatro referenciado pelo reflog
- git archive --format zip --output  nome_do_arquivo.zip branch_desejada -> cria um arquivo do formato escolhido com base na branch entregue

# private branch

