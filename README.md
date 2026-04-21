# 📘 Curso de Git

## Introducción

Este trabajo práctico individual surge de los apuntes que tomé en un curso de Git, específicamente enfocado en las herramientas y flujos de trabajo relevantes para mi postulación a la Sociedad Científica de Estudiantes de Sistemas e Informática (SCESI).

Durante el curso, cubrimos desde los principios básicos del control de versiones hasta la gestión de ramas y la colaboración remota.

## Clase 1️⃣

  ### ¿Ques es git?
  Git es un sistema de control de versiones distribuido.

  En otras palabras cada cambio que se hace git lo guarda como un CheckPoint si pasa algo malo puedes retroceder .

  En conclusion tus errores no son permanentes siempre y cuando hagas commits.

  ### Historia de Git

  Linus Torvalds conocido por sus proyectos como Linux y Git creados casi como una consecuencia no deseada por su deseo de no tener que trabajar con demasiada gente.

  Antes de Git el kernel de Linux dependía de una herramienta llamada BitKeeper.
  
  Aunque era eficiente era software privado pero Bitkeeper fue ofrecido gratis solo para el proyecto linux una exepcion incluso podia decirse un pacto de caballeros.
  
  En 2005,BitMover la empresa detrás de BitKeeper cortó el acceso gratuito por acusaciones de ingeniería inversa y malentendidos y ego.

  A causa de eso el desarrollo de linux se queso sin una herramienta para gestionar la colosal cantidad de lineas de codigo que tenia.

  Sin embargo Linus Torvalds no se quedaria con los brazos cruazados y a raiz de eso se encerro aproximadamente 2 semanas y creo su propia herramienta de control de versiones.

  Pero hay que saber que Linus no creó Git para el mundo sino porque ya no confiaba en nadie ni en licencias externas quería algo que nadie pudiera quitarle.

  En conclusion las mejores herramientas a veces no nacen de la calma sino del conflicto y la rabia convirtiéndose en el lenguaje universal de la programación.

  ### Instalacion de Git

  Dependiendo en el sitema operativo que te encuentres Git se instala de diferentes formas: 

     En windows es descargando el archivo .exe desde la pagina de Git

     En Linux la situacion es diferente ya dependiendo en que distribucion estes el comando puede variar pero eso esta en su pagina.

     ejemplo:
      debian y derivados

         -sudo apt install git

      Arch y derivados

         -sudo pacman -S git

  Y finalmente para ver si la intalacion fue correcta verificamos con el comando:

      - git --version        

  ### Configuraciones Basicas

  Para poder empezar a utilizar lo correcto es poner datos a Git el nombre y un Email pero tomando en cuenta que el Email tiene que ser el mismo que se usara para la posterior creacion de una cuenta en Github.

  Los comandos son:

    Para el nombre

      -git config --global user.name "Tu Nombre"

       nombre completo    

    Para el Email

      -git config --global user.email "tu_correo@ejemplo.com"

   Finalmente comprobamos si los datos son correctos con:

    -git config --list   