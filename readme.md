#EJERCICIO 1
## Que comando utilizaste en el paso 11?  Por que ?
<p><code>git reset --hard HEAD~1</code> (estando en la rama <em> styled</em>)</p>
<p>Es necesario usar --hard para que se elimine el contenido del working copy.</p>
<br>

## Que comando o comandos utilizaste en el paso 12?  Por que ?
<p><code>git reflog y luego git reset 5ff202f</code></p>
<p>Listamos los commitss para ver cuál es el ID del commit y hacemos un git reset al ID del commit al que queremos volver</p>
<br>
## El merge del paso 13, Causo algun conflicto?  Por que?
<p><code>git merge master</code>. No me dio conflicto, me ponía que estaba al día.</p>
<blockquote>No habría diferencia entre los dos.</blockquote>
<br>

## El merge del paso 19, Causo  algun conflicto? Por que?
<p><code>git checkout</code< styled y luego <code>git merge htmlify</code>. Se produce un conflicto en git-nuestro.md haciendo el fast-forward</p>
<br>

## El merge del paso 21, Causo  algun conflicto?  Por que?
<p>Si, Nos quedamos con el contenido del fichero de la rama styled. Hacemos un git status y vemoms que ya se han resuleto los conflictos y hacemos un git commit y nos devuelve: [styled c4a7917] Merge branch 'htmlify' into styled</p>
<br>
## Que comando o comandos utilizaste en el paso 25?
<p><code>git log --graph --decorate --pretty=oneline</code></p>
<br>
## El merge del paso 26, Podria ser fast forward?  Por que?
<p>No, porque no formaban una lista y es necesario un nuevo commit</p>
<br>
## Que comando o comandos utilizaste en el paso 27?
<p><code>git reset HEAD~1</code></p>
<br>
## Que comando o comandos utilizaste en el paso 28?
<p><code>git reflog</code> y luego <code>git resset f00c7d7</code></p>
<br>
## Que comando o comandos utilizaste en el paso 29?
<p><code>git branch -D title</code></p>
<br>
## Que comando o comandos utilizaste en el paso 30?
<p><code>git reflog</code> y  <code>git reset 6c8fd3b</code></p>
<br>
## Que comando o comandos usaste en el paso 32?
<p><code>git reflog</code> y <code>git reset 6c8fd3b</code></p>
<br>
## Que comando o comandos usaste en el punto 33?
<p><code>git reflog</code> y <code>git reset 83fe554</code></p>
<br>
