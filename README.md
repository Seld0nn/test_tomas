# test_tomas

Tutorial de como usar Git y GitFlow

descargar repo

```console
git clone [link]
```

Ver estado de repositorio

```console
git status 
```

## Para actualizar estados respositorios

```console
git fetch
```

cargar cosas al repo

```console
git add -A
git commit -m "mensaje"
git push
```

fist commit de una branch antes del git push habrá que hacer

```console
git push --set-upstream origin nombrebranch
```

Como saber que cosas hay en cada branch

```console
git branch [name_new_branch]
git checkout [name_new_branch]
```

la branch que se Crear es un copia de la branch en que te encuentras

Cambiar de branches

```console
git checkout [name_branch]
```
