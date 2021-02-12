# Git-Tutorial



### ¿Que es Git?

Git es un control de versiones, es decir:

Es un gestor (controlador) de los cambios que se realizan en un producto (software), es una herramienta para poder controlar las modificaciones que se realizan en un proyecto de una forma muy ordenada, limpia y sencilla.



#### Documentación oficial Git-Hub (español)

[Doc. GitHub](https://docs.github.com/es/github)



### ¿Cómo empezar?

Lo primero será crearnos un usuario en la web de [GitHub](https://docs.github.com/es/github).

A continuación nos tocara descargarnos Git para nuestro sistema operativo.

(En este caso Windows):

* [Git](https://gitforwindows.org)

Una vez tengamos instalado Git comenzamos a utilizarlo mediante la terminal de nuestro pc (la consola de comandos), recomendamos utilizar el terminal Git Bash el estará disponible tras la instalación de Git.

Este lo podemos abrir desde el buscador de Windows buscando: "Git Bas" o realizando click derecho y seleccionando "Git Bas Here". (Esto nos abrirá directamente el terminal, situado en la ruta que hemos realizado el click derecho).

[![Terminal Bash](https://i.postimg.cc/fbHXBdvC/Captura.jpg)](https://postimg.cc/SXMJKJ3Y)



A continuación enlazaremos nuestra terminal con nuestra cuenta de GitHub, mediante los siguientes comandos:

```bash
// Introduciremos el nombre de usuario en GitHub
git config – global user.name 'tu nombre'

// Introduciremos el email de GitHub
git config – global user.email 'tu@email.com'
```

Seguramente nos pedirá la propia terminal, nuestra contraseña también con esto ya tendríamos el terminal listo para nuestro primer repositorio.

### Comandos básicos terminal

```bash
** Terminal Git-Bash **
// Cambiar de directorio (carpeta)
cd nombre-del-directorio

//Volver hacia atras en el directorio (carpeta anterior)
cd ..

//Crear directorio (carpeta)
mkdir nombre-de-la-carpeta

//Borar directorio (carpeta)
rmdir  nombre-de-la-carpeta
```







