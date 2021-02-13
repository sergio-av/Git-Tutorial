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



### Primer repositorio (proyecto) en GitHub

Lo primero será crear el repositorio en la web [GitHub](https://docs.github.com/es/github), desplazándonos hacia la pestaña repositorio de nuestro perfil y una vez en ella hacer click en el botón New.

[![nuevo-Repositorio.jpg](https://i.postimg.cc/s2vF3mYM/nuevo-Repositorio.jpg)](https://postimg.cc/Y4KD31y7)



A continuación:

- Daremos nombre al repositorio

- Seleccionaremos su privacidad 

- Crearemos una breve descripción (opcional)

- Como buena practica siempre añadiremos el Readme, marcando la casilla "add Readme".

  

  [![imagen-2021-02-13-001418.png](https://i.postimg.cc/V6gX4qhF/imagen-2021-02-13-001418.png)](https://postimg.cc/WFDD1kTD)

  

  Con el repositorio ya creado solo queda clonarlo (descargarlo e instarlo) en nuestro repositorio local (la carpeta que deseemos utilizar) para lo cual vamos a utilizar la terminal Git Bash:

  - Comenzamos clonando el repositorio desde la web

    [![imagen-2021-02-13-002705.png](https://i.postimg.cc/Gp1M5jM0/imagen-2021-02-13-002705.png)](https://postimg.cc/mP8Nc7fV)

  - Luego Abrimos la terminal en la carpeta que queramos iniciar el proyecto 

    ```bash
    //Para clonar el repositorio y poder empezar a trabajar con el:
    git clone el-url-del-repositorio  //En bash se pega con Alt + Insert 
    ```

    

  Con esto ya tendríamos nuestro repositorio de GitHub listo para poder trabajar en el.

### 







