### Programación 1
* Profesor: Jonhatan Mircha (Jon)

En esta materia estamos viendo lo que está viendo a continuación.... esto XD, Ok no pero estamos viendo las bases fundamentales para el uso de de la terminal de comandos y a su vez estamos viendo el uso de "_VS_" (Visual Studios), el uso del lenguaje MarkDown, Git y GitHub (hago enfasis de que Git y GitHub no es lo mismo) si no Jon me mata.

### Fundmamentos de la computación 
* Profesor: Osiel Morales
En esta materia estamos viendo los sistemas operativos y su arquitectura de cada uno, conocer el lenguaje "_C_" y como programarlo, algoritmos, diagramas de flujo y practicas de ello.

### Introducción a la ciberseguridad
* Profesora: Cynthia 
En esta materia estamos viendo como es el mundo laboral de nuestra carrera de cibersguridad, conceptos, uso de lenguaje, que se debe hacer en ciestras situaciones y a donde queremos llegar en nuestra carrera sobre alguna especialización, terminos que se usan frecuentemente.

### Matematicas 1
* Profesor: Rojo Trejo 

En esta materia estamos repasando temas de anterioridad y reforzandolos, aprendiendo funciones lineales,cuadraticasa, cortaduras de Dedekind, cifrados en binario 

### Algebra 
* Profesor: Hugo 

En esta materia estamos viendo los vestores y matrices, como son sus operaciones y como programarlar en python, suma,resta,multiplicación de vectores y matrices, encontrar la determinante menor de cada una.

---
## Creando la versión 1.0.0 de este repositorio 

#### ¿Cómo se inicializa un repositorio en Git?

El primer paso para inicializar un repositorio es crear una carpeta en tu zona local (computadora), despues es entrar a Visual Studios e ir a a una opción que se llama "_control de código fuente_", en ese apartado habrá una opción donde diga "_crear repositorio_". Ya al estar en este paso ya tienes una cuarta parte del proceso completado.

### ¿Cómo creas un repositorio en GitHub?

En este paso explicaré como poder vincular tú repositorio a la plataforma de GitHub, para esto necesitaras una cuenta en GitHub. Ya tener tu cuenta creada entraras a una opción que se llama _"crear repositorio"_ o en su caso "_new_", ya que estes ahí tendras que ponerle algún nombre a tu repositorio y una breve explicación sobre que será tu repositorio y podrás decidir si será privado o público; depues de esto la plataforma te lanzará un código URL con la finalidad de vincular del local al remoto tu repositorio.

### ¿Cómo vinculas un repositorio local de Git con uno remoto en GitHub?

Al tener los dos pasos anteriores completados vamos a entrar nuevamente a _VS_ para proseguir con la vinculación aqui tendras que abrir la terminal de comandos y abrir la terminal _Git_ ¿cómo?, con el siguiente comando:

`Ctrl + ñ` 

Luego ingresarás un comando que empezará el flujo básico de Git, es el siguiente:

`git add .`

Con este comando empezarás a poner tu repositorio en el estado _stage_, es el inicio de vinculación remota.
Luego ingresarás el siguiente comando:

`git commit `

En este paso escribiras un mensaje entre comillas para definir que modificaciones se hicieron en el repositorio, sin embargo como será el primer _commit_ normalmente se pone _primer commit_, este paso lleva al repositorio al estado _commited_.

Al ser la primera vez que vinculas el repositorio tendrás que poner un comando que dirija los cambios al URL en donde creaste el repositorio en GitHub.

`git url del repositorio de GitHub`

Con este comando ya estará parte de la vinculación y donde se va a dirigir los cambios. El siguiente comando sería para poder lanzar los cambios.

`git push`

Con este comando ya estáras terminando de vincular el repositorio etrando al estado _remote_ y para poder verificar que se haya echo correctamente el proceso ve a la página de GitHub y carga para que se actualice el trabajo y se muestre realizado el trabajo.
