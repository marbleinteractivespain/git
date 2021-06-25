#EJERCICIO 1
## Que comando utilizaste en el paso 11?  Por que ?
<p>**git reset --hard HEAD~1** (estando en la rama <em> styled</em>)</p>
<p>Es necesario usar --hard para que se elimine el contenido del working copy.</p>
<br>

## Que comando o comandos utilizaste en el paso 12?  Por que ?
<p>**git reflog** y luego **git reset 5ff202f**</p>
<p>Listamos los commitss para ver cuál es el ID del commit y hacemos un git reset al ID del commit al que queremos volver</p>
<br>
## El merge del paso 13, Causo algun conflicto?  Por que?
<p>**git merge master**. No me dio conflicto, me ponía que estaba al día.</p>
<blockquote>No habría diferencia entre los dos.</blockquote>
<br>

## El merge del paso 19, Causo  algun conflicto? Por que?
<p>**git checkout** styled y luego **git merge htmlify**. Se produce un conflicto en git-nuestro.md haciendo el fast-forward</p>
<br>

## El merge del paso 21, Causo  algun conflicto?  Por que?
<p>Si, Nos quedamos con el contenido del fichero de la rama styled. Hacemos un git status y vemoms que ya se han resuleto los conflictos y hacemos un git commit y nos devuelve: [styled c4a7917] Merge branch 'htmlify' into styled</p>
<br>
## Que comando o comandos utilizaste en el paso 25?
<p>**git log --graph --decorate --pretty=oneline**</p>
<br>
## El merge del paso 26, Podria ser fast forward?  Por que?
<p>No, porque no formaban una lista y es necesario un nuevo commit</p>
<br>
## Que comando o comandos utilizaste en el paso 27?
<p>**git reset HEAD~1**</p>
<br>
## Que comando o comandos utilizaste en el paso 28?
<p>**git reflog** y luego **git resset f00c7d7**</p>
<br>
## Que comando o comandos utilizaste en el paso 29?
<p>**git branch -D title**</p>
<br>
## Que comando o comandos utilizaste en el paso 30?
<p>**git reflog** y **git reset 6c8fd3b**</p>
<br>
## Que comando o comandos usaste en el paso 32?
<p>**git reflog** y **git reset 6c8fd3b**</p>
<br>
## Que comando o comandos usaste en el punto 33?
<p>**git reflog** y **git reset 83fe554**</p>
<br>
