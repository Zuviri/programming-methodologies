# Introducción a Git

## Configuración de git
git config

### Configuración del nombre del autor
git config --global user.name "Zuviri26"

### Configuración del email del autor
git config --global user.email "2630326@upv.edu.mx"

### Configuración de la rama master a main
git config --global init.defaultBranch main

## Repositorio
Tres áreas: untracked files -> staging area -> git repository

## Inicializar un repositorio de git
git init

## Estado del repositorio
git status

## Agregar todos los archivos untracked al área de staging
git add -A

## Agregar un commit del área de staging a la base de datos de git
git commit -m "Mensaje"

## Conectar el repositorio local con GitHub
git remote add origin https://github.com/Zuviri/programming-methodologies

## Renombrar la rama principal a main
git branch -M main

## Subir los cambios a GitHub
git push -u origin main