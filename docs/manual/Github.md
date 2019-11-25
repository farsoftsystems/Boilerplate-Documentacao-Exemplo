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

teste