1. ¿Qué es git?

Es un sistema de control de versiones creado por Linus Torvalds, que controla o administra las distintas versiones de un programa. 

2. ¿Por qué queremos utilizar git?

Para controlar/administrar un proyecto que va a crecer a medida que el tiempo va haciendo cambios (archivos, configuraciones, escrituras de códigos, etc.); contribuir con múltiples desarrolladores desde cualquier parte del mundo, o trabajar en un proyecto personal de forma profesional; también nos permite manejar los cambios cuando hacemos una alteración en el código, navegar en cualquier punto de la versión del programa y modificarlo.

3. ¿Qué es el bash que instala git?

Es un tipo de consola (lenguaje de comandos), que trae los conceptos de Unix

4. Describa los estados (working directory, staging area, repository)

Working directory: área donde trabajamos con nuestros archivos antes de crear la primera versión de nuestro software.
Staging area: área donde agregamos los archivos que vamos a preparar para el guardado
Repository: área donde se guarda el cambio.

5. Describa el flujo para crear un nuevo repositorio git.

Primero creamos una carpeta llamada "proyecto" en escritorio.
Se debe abrir un terminal (abrir consola de window/tipo cmd/escribir Desktop/cd proyecto/git init)


6. Describa el flujo para agregar un archivo simple al repositorio.

git commit

7. Describa el flujo para cambiar el archivo agregado y guardar los cambios en el repositorio.

Cuando nos encontremos en el estado "working directory" se debe utilizar el comando "git add" para agregar el archivo al estado "staying area", donde podremos cambiarlo y luego usaremos el comando "git commit" para guardarlo en el repository

8. ¿Cómo hago para ignorar un archivo o carpeta?

Creamos un archivo que llamaremos ".gitignore", dentro de esta carpeta escribiremos el nombre de los archivos que deseamos ignorar.

9. Explique qué es un branch. Dé un pequeño ejemplo de cómo haría uno.

Es un comando llamado que se usa para listar, crear o borrar ramas. Haría uno usando el comando "git branch", luego se abre una carpeta llamada "master", donde se guardarán los cambios que hagamos.

10. ¿Qué hago con 'git add'?

Es para poder pasar los archivos del working directory al staging area

11. ¿Cómo cambiamos de un branch a otro?

Utilizando el comando "git branch" seguido del nombre de la versión alternativa que deseamos.

12. Investigue qué es Markdown y responda todas las preguntas anteriores en este lenguaje (con el nombre de archivo RESPUESTAS.md). Súbalo al repositorio.

Markdown es un lenguaje de marcado ligero creado por John Gruber que trata de conseguir la máxima legibilidad y facilidad de publicación tanto en su forma de entrada como de salida, inspirándose en muchas convenciones existentes para marcar mensajes de correo electrónico usando texto plano.
