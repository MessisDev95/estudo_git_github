
# GIT | Manipulando branchs
_Branch é uma ramificação do código, em que podemos trabalhar diferentes funcionalidades fora do escopo principal projeto._ 


## 📝 Trabalhando com branchs
- No CMD/PowerShell
### 1- Crie uma branch apartir da main do projeto:

````bash
git checkout -b nome_da_branch
````
### 2- Para mudar de branch:
````bash
git checkout nome_da_branch_desejada
````
### 3- Para listar branchs do repositório:
````bash
git branch
````
### 4- Para verificar os últimos commits de cada branch:
````bash
git branch -v
````
### 5- Mesclando conteúdos das branchs:
````bash
git merge nome_da_branch_desejada
````
Obs: Fazendo isso, misturamos os conteúdos da branch desejada com a branch atual.

### 6- Para excluir uma branch:
````bash
git branch -d nome_da_branch_desejada
````
## 📝 Alguns comandos úteis:
- ### Baixando alterações feitas no GITHUB no repositório local
````bash
git pull
````
- ### Baixando alterações do repositório remoto sem misturar com o local:
````bash
git fetch origin nome_da_branch
````
- ### Para ver a diferença entre a baixada e a remota após o `fetch`:
````bash
git diff repositorio_local origin/branch_do_remoto
````
- ### Misturando a branch baixada remota com a local:
````bash
git merge origin/nome_da_branch_baixada
````
- ### Ao Haver um conflito:
Para ver situação do conflito
````bash
git status
````
Para escolher a versão local:
````bash
git checkout --ours nome_do_arquivo
git add nome_do_arquivo
````
Para escolher a versão remota:
````bash
git checkout --theirs nome_do_arquivo
git add nome_do_arquivo
````
- ### Baixar uma branch do repositório:
````bash
git clone URL_do_repositorio --branch nome_da_branch --single-branch
````
- ### Podemos tambem "“guardar na gaveta tudo que ainda não foi comitado", para trabalhar em outras funcionalodades:
````bash
git stash
git stash list
````
Obs: o stash list é para listar oque está "guardado".
- ### Ao querer recuperar o trabalho "guardado", podemos usar:
````bash
git stash pop
````
Obs: isso apaga o trabalho feito antes do `stash` inicial, mas podemos usar o stash apply para salvar as alterações no que foi guardado:
````bash
git stash apply
````
