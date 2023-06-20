## Git para Tester | Analista Qualidade | QAs

### Comandos que mais utilizamos no Git

```
git status
```
Geralamente utilizado para exibir o que foi modificado dentro da pasta/projeto que você está alterando.

```
git init
```
Geralmente utilizado para exibir que o pacote/projeto vai ser iniciado o versionamento com os comandos Git.

```
git merge
```
Geralmente utilizado para realizar um merge entre dois branchs separadas.
(União de dois códigos, geralmente código de versão final).

```
git checkout -b nomedadabranch
```
Geralmente utilizado  para criar uma nova branche fazer uma navegação para a mesma.

```
git fetch
```
Geralmente utilizado para dar um _REFRESH_  de todas as branchs criadas no repositório.

```
git checkout  nomedadabranch
```
Geralmente utilizada para modificar da sua branch atual para a branch no qual você está passando o comando.

```
git commit -m "Descrição do commit"
```
Geralmente utilizado para descrever o que você está subindo para o repositório.

```
git push
```
Geralmemte utilizado para subir de fato as suas alterações para a branch que você está a tornar seu código visível para todos.

O que significa _BRANCH_ ? 

Branch, em tradução literal, significa "ramo". No mundo da programação, ela tem o mesmo  siginificado: uma branch é uma ramificação do seu projeto. Os repositórios no GitHub funcionam  como uma árvore.

Agora vamos subir nosso Readme.

Abra o GitBash dentro da pasta do seu repositório local (pc)

Use o comando:

```
git status
```

Para visualizar os arquivos para subir.

Depois use o comando: 
```
git add .
```
Para adicionar os arquivos.

Agora vamos fazer o commit:
```
git commit -m "Descrição do que está subindo"
```
Enfim vamos fazer o push:
```
git push origin main
```
Feito! 

## Subindo para o Gitlab

Depois do repisitório criado no GitLab, vamos subir nossa pasta para o GitLab.

Primeiro vamos confirmar nosso user.
```
git config --global user.name "Fabrício Luis Perrone"
```
Logo em seguida vamos confirmar nosso e-mail.
```
git config --global user.name "Fabrício Luis Perrone"
```
Vamos dar um comamdo PWD para vermos se estamos no camninho certo. Um ls para vermos todos os arquivos da pasta.

Vamos fazer a conexão com o repositório remoto.
```
git remote add origin https://gitlab.com/suportesubzeroinformatica/git-para-qas.git

```
```
git add . 
```
Ponto (.) adiciona tudo que tem dentro da pasta.

```
git commit -m "Subindo o projeto"
```
Por último vamos fazer o push

```
git push -u origin master
```
Feito!
