# GIT Básico

## Instalación

Instalación desde el asistente de Git

## Comandos para credenciales en nuestro equipo

``` 
git config --global user.name "norellag2"
git config --global user.email "norellag2@gmail.com"
```

## Como crear un repositorio git
```
git init
```

## Comprobar el estado de git
Ver la situación en la que están los cambios desde el último commit
```
git status
```
## Añadir archivos al staging area
Añade todos los cambios pendientes
```
git add -A
```
## Crear un commit 
para guardar un conjunto de cambios y crear un punto de control usamos los commit
```
git commit -n "mensaje del commit"