GITHUB
---------------------------------------------------------------

- Control de Versiones Distribuidos (DVCS)

git config --global user.name "<nombre_usuario>"
git config --global user.email "<email>"

1) Empezar el proyecto:

    git init  -> Crea un carpeta oculta .git donde guarda toda la configuración.

2) Cambiar la rama de nombre:

    git branch -m <nombre_nuevo_para_la_rama>

    git branch: Este es el comando básico para trabajar con ramas en Git.
    -m: Es la opción que se utiliza para cambiar el nombre de la rama.


3) Estado del proyecto:

    git status

4) Hacer fotos de ficheros.

    - git add <nombre_del_fichero>
    - git add .  -> Todos los ficheros ( no es recomendable)

5) Salvar foto de los ficheros.

    git commit -m "<mensaje>"

    git commit: Este comando se utiliza para confirmar los cambios realizados en el área de preparación y agregarlos al historial de versiones del repositorio.

    La opción -m se utiliza para proporcionar un mensaje de confirmación en línea con el comando. El mensaje entre comillas ("Mi primer commit") es un comentario que describe brevemente los cambios realizados en este commit. Es una buena práctica escribir mensajes descriptivos y significativos para que otros desarrolladores (o tú mismo en el futuro) puedan entender fácilmente el propósito del commit.

    Cuando se realiza una fotografía, git le asigna un HASH ( código único de identificación).