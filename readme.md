# Inicializando o git Local

Primeiro confira se o git está instalado:

```bash
git --version
```
# Segundo configurar usuario
```
git config --global user.name "vitoria carolina"
git config --global user.email "costavitoriacarolina@gmail.com"
```
# Terceiro passo inicializar local
```
$cd Documents

$mkdir notas

$cd notas
```

```
$git init
```
#Exibe o a condição da árvore de trabalho
 git status

#Adiciona um arquivo
 git add <filename ou . >

#Restaura os arquivos 
 git restore --staged <filename ou . >

#Lista, cria ou exclui ramificações
 git branch <branchname>

#Altera ou restaura arquivos
 git checkout <branchname>

#Checa nome ou referencia
6 - git checkout -b <branchname>

#Inicializa, atualiza ou inspeciona
7 - git commit -m "<description>"

#Atualiza refs
8 - git push

#Cria, lista, renomeia e exclui ramificaçõs
9 - git branch -D <branchname>

#Faz o download dos objetos e refs
10 - git fetch

#P
11 - git pull
