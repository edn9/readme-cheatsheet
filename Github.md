## Comandos Git
Configurando usuario global:

`git config --global user.name "username"`

`git config --global user.email "user@email.com"`

Baixando o projeto para a maquina:

`git clone https://gitlab.com/repo`

Vendo se o projeto tem algum update:

`git pull`

Adicionando arquivos alterados para envio:

`git add .`

Comentando o que você alterou nestes arquivos que ira enviar:

`git commit -m "teste de envio"`

Enviando:

`git push`

Mudando o branch:

`git checkout branchName`

Criando o branch e mudando pra ele:

`git checkout -b branchName`

Que seria o mesmo que:

```
git branch branchName
git checkout branchName
```

Ver diferenças entre branch:

`git diff master dev1`


Ver diferenças de um arquivo especifico ao decorrer dos commits:

`gitk --follow -- resources/views/pages/admin/index.blade.php`

Ver diferenças do mesmo arquivo em commits/branchs diferentes:

`git diff branch1:path/to/file branch2:path/to/file`

Delete local branch:

`git branch -d branch_name`

Dar merge:

```
git checkout master
git merge dev1
```

Dar merge e limpar os branch's, deixando tudo linear:

```
git checkout experiment
git rebase master
```


Outros comandos e mais exemplos:

https://rogerdudler.github.io/git-guide/

https://git-scm.com/book/pt-br/v1/Ramifica%C3%A7%C3%A3o-Branching-no-Git-B%C3%A1sico-de-Branch-e-Merge

http://guides.beanstalkapp.com/version-control/branch-comparisons.html

https://git-scm.com/book/pt-br/v1/Ramifica%C3%A7%C3%A3o-Branching-no-Git-Rebasing
