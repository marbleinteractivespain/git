#EJERCICIO 1
## Que comando utilizaste en el paso 11?  Por que ?
**git reset --hard HEAD~1** (estando en la rama _styled_)
Es necesario usar _--hard_ para que se elimine el contenido del working copy.</p>
<br>

## Que comando o comandos utilizaste en el paso 12?  Por que ?
**git reflog** y luego **git reset 5ff202f**
Listamos los commitss para ver cuál es el ID del commit y hacemos un git reset al ID del commit al que queremos volver
<br>
## El merge del paso 13, Causo algun conflicto?  Por que?
**git merge master**. No me dio conflicto, me ponía que estaba al día.
<blockquote>No habría diferencia entre los dos.</blockquote>
<br>

## El merge del paso 19, Causo  algun conflicto? Por que?
**git checkout** styled y luego **git merge htmlify**. Se produce un conflicto en git-nuestro.md haciendo el fast-forward
<br>

## El merge del paso 21, Causo  algun conflicto?  Por que?
Si, Nos quedamos con el contenido del fichero de la rama styled. Hacemos un git status y vemoms que ya se han resuleto los conflictos y hacemos un git commit y nos devuelve: [styled c4a7917] Merge branch 'htmlify' into styled
<br>

## Que comando o comandos utilizaste en el paso 25?
**git log --graph --decorate --pretty=oneline**
<br>

## El merge del paso 26, Podria ser fast forward?  Por que?
No, porque no formaban una lista y es necesario un nuevo commit
<br>

## Que comando o comandos utilizaste en el paso 27?
**git reset HEAD~1**
<br>
## Que comando o comandos utilizaste en el paso 28?
**git reflog** y luego **git resset f00c7d7**
<br>

## Que comando o comandos utilizaste en el paso 29?
**git branch -D title**
<br>

## Que comando o comandos utilizaste en el paso 30?
**git reflog** y **git reset 6c8fd3b**
<br>

## Que comando o comandos usaste en el paso 32?
**git reflog** y **git reset 6c8fd3b**
<br>

## Que comando o comandos usaste en el punto 33?
**git reflog** y **git reset 83fe554**
<br>
