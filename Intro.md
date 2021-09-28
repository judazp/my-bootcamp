# Intro a Git

Definición: Sistema de control de versiones. Puedo ver el histórico de cambios en los archivos de mi proyecto.
Además con git puedo trabajar en remoto y compartir mis cambios con el resto de mis compañeros de proyecto.

## ¿Todos mis archivos son git?
No, para poder meter los archivos en el proyecto tengo que ejecutar un comando especial. A un proyecto en git se le llama **repositorio**.

## ¿Qué es un proyecto?
Un proyecto es una carpeta que dentro tiene todas las carpetas y archivos que pertenecen al mismo.

## ¿Cómo creo un repositorio git?
1. Abrir un terminal en la carpeta raíz
2. Ejecutar en el terminal de comando
> npm init

Desde aquí el proyecto con esa carpeta raíz es un repositorio git.

## init 
inicializa un repositorio en la carpeta donde los pongo

## status
Me indica el estado de un repositorio
- que rama estoy
- los commits
- que archivos se han modificado
- Que archivos todavía no existen en un repositorio git

## status
Me indica el estado del repositorio
- Rama en la que estoy
- Commits
- Archivos que se han modificado
- Archivos que todavía no existen en el repositorio git

## add
Añadir los cambios que haya sufrido el directorio de trabajo en el área de “staging”

Puede añadir todos los archivos del directorio de trabajo, o sólo los que yo seleccione. 

Para añadir todo ( > git add . )

Si sólo queremos añadir archivos concretos, debemos poner el nombre del archivo/s después del add separados por espacio

Para añadir concretos >git add demo.md demo.txt

## commit
Guarda los cambios que haya en el área de “staging” en el repositorio

EL parámetro -m es obligatorio. Sirve para indicar el mensaje del commit (un mensaje que describe que cambio se está haciendo)

 git commit -m “Mi mensaje descriptivo”

Parámetro -a subo todo lo que tengo en el directorio de trabajo en el que me encuentre


# HTML
- usa ! para coger el doctype
- Utiliza Head unicamente para poner el título y el stylesheet
- llama al css como link <link rel="stylesheet" href="style.css">
- todo el contenido va en el body
- 