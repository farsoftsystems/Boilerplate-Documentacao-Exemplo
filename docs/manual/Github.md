# Criar um repositório no Github

## Passo a Passo

1. Logar-se na conta do git
2. Entrar no seu git: https://github.com/seulogin
3. Clicar no botão New e preencher os dados conforme a imagem abaixo:

![Github](/assets/img/github.jpg  "Criando um novo Repositório")

4. Referenciar o repositório ao projeto

```
echo "# Boilerplate-Documentacao-Exemplo" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:farsoftsystems/Boilerplate-Documentacao-Exemplo.git
git push -u origin master
```

Rodar os comandos:

```
git init
git add --all
git commit -m "Primeira carga do projeto"
git remote add origin git@github.com:farsoftsystems/Boilerplate-Documentacao-Exemplo.git
git push -u origin master   (somente a primeira vez, depois é só git push)
```

## Comandos Git

- Mudar e já criar a branch nova
```
git checkout -b NOMEDABRANCH (recomendo minusculo)
```

- Saber aonde está (qual branch)
```
git branch
```

- Fazer o merge (a união do seu branch com a master) depois de ter feito as devidas implementações/alterações

```
git add --all
git commit -m "escreve o que quiser referenciar"

git checkout master
## Dar o comando abaixo para verificar mudanças
git pull 
## Dar o Merge
git merge nomedabranchcriadaanteriormente

```

- Comando para subir as alterações
```
git push -u origin master (primeira vez)

##depois somente:

git push

```

- Comando para deletar as branchs
```
$ git push -d <remote_name> <branch_name>
Exemplo: git push -d origin junior
$ git branch -d <branch_name>
```

- Deleção

```
## Deletar Remotamente
git push -d origin nomedabranchquehaviasubido

## Deletar Local
git branch -d nomedabranchquehaviacriado
```




