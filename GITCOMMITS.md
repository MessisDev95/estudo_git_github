# GIT | Manipulando commits

## 📝 

- ###  Verificar situação do repositório:
````bash 
git status
````
- ### Ao fazer uma modificação indesejada e desejar desfaze-la:
````bash
git restore arquivo_modificado
````
Obs: se apagou um arquivo e não lembrar o nome use o comando (git status) 
- ### Verificar histórico de commits:
````bash
git log
````
- ### Alterar mensagem do último commit:
````bash
git commit --amend -m"sua_nova_mensagem"
````
- ### Voltar para commits anteriores:
````bash
git reset --soft hash_do_commit
````
- ### Para obter histórico de alterações:
````bash
git reflog
````



