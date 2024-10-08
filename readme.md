# GIT RAMAS (BRANCHES)

```sh
git init
```

## VER EL STATUS DE LOS ARCHIVOS

```sh
git status
```

## GIT ALIAS... 

```sh
git congig --global alias.st "status --short" 
git config --global alias.c "commit -m"
git config --global alias.a "add"
git config --global alias.st "status --short"
```
## VER LAS DIFERENCIAS ENTRE WR Y LR

```sh
git diff
```

## VER EL CONTENIDO DE CADA COMMIT

```sh
git show <numero-hash>
```

## CREAR UNA RAMA

````sh
git branch <nombre-rama> #crea una rama y nos deja en la actual
git brach feature/ramas #ejemplo
git switch -c <nombre-rama> #crea una rama y nos mueve a la rama que se creo
````

## ME MUEVO ENTRE RAMAS

````sh
git switch <nombre-rama>
git switch feature/ramas #ejemplo
````
