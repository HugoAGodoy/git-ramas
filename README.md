# GIT RAMAS (Branches)

## Crear un repositorio

```sh 
git init
```

# Ver el status de los archivos

```sh 
git status
```

## Git Alias

```sh 
git config --global alias.st "status --short"
git config --global alias.a "add"
```

# Ver las diferencias entre WD (Working directory/lo que tengo actual) y LR (Local repository/lo que esta guardado)

```sh 
git diff
```

## Ver el contenido de cada commit

```sh 
git show <numero-hash>
```
## Crear una rama 

```sh
git branch <nombre-rama> # Crea una rama y nos deja en la rama actual
git branch feaure/ramas # ejemplo
git switch -c <nombre-rama> # crea una rama y nos mueve a la rama que se creó
```
# Me mueve entre ramas 

```sh
git switch <nombre-ramas>
git switch feaure/ramas #ejemplo
```


