inicializar o git em uma pasta sem a pasta .git dentro
git init

adicionar o arquivo modificado pra fazer o commit
git add . 
ou
git add <nome do arquivo>

"embrulha" as alterações adicionadas com uma mensagem
git commit

visualiza o estado atual de commits e mudanças
git status

sincroniza o repositório local (pc) com o remoto (github)
git push

mostra o link do github
git remote -v 



## branches
criando uma nova branch e indo para ela
git checkout -b <nome da branch>

vincular nova branch local com nome branch remota (só precisa ser feito uma vez)
git push --set-upstream origin <nome da branch>