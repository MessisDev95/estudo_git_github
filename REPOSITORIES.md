
# GIT | COMANDOS

Comandos úteis para usar GIT e GITHUB.


## 📝 Criar repositório localmente:
- No CMD/PowerShell
### 1- Crie um arquivo de projeto:

````bash
mkdir nome_projeto
cd nome_projeto
````
### 2- Inicie o arquivo como repositório GIT:
````bash
git init
````
### 3- Adicione arquivos ao seu 1° commit:
````bash
git add .
````
Obs: Nesse caso (.) adiciona todos.

### 4- De uma descrição ao seu commit:
````bash
git commit -m "Primeiro commit."
````

### 5- Defina em qual segmento do código será seu commit:
````bash
git branch -M main
````
### 6- Adicione o link do repositório GITHUB onde o arquivo será armazenado:
````bash
git remote add origin URL_do_repositório
````
### 7- Enviei seu arquivo para o GITHUB:
````bash
git push -u origin main
````

## Se já existir um repositório:
````
git remote add origin URL_do_reposiório
git branch -M main
git push -u origin main
````

## 📝 BAIXAR UM REPOSITÓRIO DO GITHUB:

- ###  Copiar repositório:
````bash
git clone URL_do_repositório_github
````
