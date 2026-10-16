---
layout: home
header:
  title: MI PORTAFOLIO CRISTIAN DEL ANGEL
  text: >
    Proyectos personales e información sobre mi, aqui podras visualizar y conocer
    mi trayecto como desarrollador web y en general como ing. en Tic´s 
  action: # action button is optional
    label: SABER MÁS...
    url: '#about'


sections:
  - type: call-to-action.html
    section_id: about
    background_style: bg-primary
    title: ¿Quien soy y cual es mi formación?
    text: Hola!, mi nombre es Cristian Eduardo y soy Ingeniero en Tecnologias de la información y sistemas (tic´s), el siguiente botón te llevará a mi autobiografia para que sepas mas de mi...
    actions:
      - title: Sobre mi
        url: '#page-top'
        class: btn-light

  - type: services.html
    section_id: services
    #background_style: bg-info
    title: Mis servicios
    services:
      - title: Soporte técnico
        text: Mantenimiento general fisico y sistematico a equipos de cómputo así como instalación de software
        icon: bi-laptop
      - title: Desarrollador web
        text: Implementación de sitios web con lógica propia y manejo de base de datos
        icon: bi-globe
      - title: Orientación técnica 
        text: Apoyo en la actualización, explicación o información de un proceso
        icon: bi-question-circle-fill
      - title: Tutorias
        text: Tutoriales y guias de apoyo en el aprendizaje de alguna tecnologia o tema específico disponible
        icon: bi-book
      - title: Software con licencia
        text: Instalación de licencias para software como antivirus y de ofimática
        icon: bi-terminal-fill
      - title: Configuraciones
        text: Actualizaciones de aplicaciones y configuraciones de preferencia
        icon: bi-tools

  - type: portfolio.html
    # this section has always ID 'portfolio'
    #section_id: portfolio
    #background_style: bg-dark
    projects:
      - title: Proyecto 1
        text: Este es el primer proyecto
        # the images are located in:
        # img/portfolio/fullsize
        # img/portfolio/thumbnails
        icon: 1.jpg
        url: '#'
      - title: Proyecto 2
        text: Este es el segundo proyecto
        icon: 2.jpg
        url: '#'
      - title: Proyecto 3
        text: Este es el tercer proyecto
        icon: 3.jpg
        url: '#'
      - title: Proyecto 4
        text: Este es el cuarto proyecto
        icon: 4.jpg
        url: '#'
      - title: Proyecto 5
        text: Este es el quinto proyecto
        icon: 5.jpg
        url: '#'
      - title: Proyecto 6
        text: Este es el sexto proyecto
        icon: 6.jpg
        url: '#'

  - type: aside.html
    section_id: aside
    title: Mis Proyectos
    actions:
      - title: Repositorio - GitHub
        url: https://github.com/CristianEddu-byte/CristianEddu-byte.github.io.git
        class: btn-light

  - type: members.html
    section_id: member
    title: Tecnologías aplicadas
    background_style: bg-info text-white
    members:
      - title: JavaScript
        text: Lenguaje de programación POO
        image: assets/img/technologies/javascript.jpg
       
      - title: HTML5
        text: Lenguaje de hipertexto para estructurar sitios web
        image: assets/img/technologies/html.jpg
        url: '#'
      - title: CSS3
        text: Lenguaje de diseño grafico
        image: assets/img/technologies/css.jpg
        url: '#'
      - title: Node js
        text: Entorno de ejecucion de lado del servidor
        image: assets/img/technologies/node.jpg
        url: '#'
      - title: Git
        text: Sistema de control de versiones 
        image: assets/img/technologies/git.jpg
        url: '#'
      - title: PostgreSQL
        text: Sistema de gestion de base de datos
        image: assets/img/technologies/postgre.jpg
        url: '#'

  - type: timeline.html
    section_id: timeline
    title: MI HISTORIA
    background_style: bg-dark text-primary
    last_image: assets/img/timeline-end.png
    actions:
      - image: assets/img/timeline/prepa.jpg
        title: |
          2017

          **Empiezo la preparatoria**
        text: >-
          En esta parte comienzo mis estudios en la preparatoria y a partir de ello 
          empiezo a considerar las carreras profesionales.
      - image: assets/img/timeline/youtube.jpg
        title: |
          2019

          **Hago un curso en html y css por hobbit**
        text: >-
          Durante mis vacaciones de la preparatoria me encuentro con un espacio libre
          y en un video de YouTube veo que puedo aprender a desarrollar sitios web, por ello como curiosidad
          checo un tutorial de html y css, entonces me interesa y profundizo en ello.
      - image: assets/img/timeline/graduacion.jpg
        title: |
          2020

          **Me graduo de la preparatoria**
        text: >-
          Me graduo del nivel medio superior y fijo mi objetivo en la educación superior.
      - image: assets/img/timeline/universidad.jpg
        title: |
          2021

          **Comienzo a estudiar la universidad**
        text: >-
          Empiezo mi carrera de ingenieria en Tecnologías de la Información y Sistemas.
      - image: assets/img/timeline/congreso.jpg
        title: |
          2024

          **Participo en el congreso de la UMAN**
        text: >-
          Presento mi proyecto "Catálogo de pila abierta", un sitio web como apoyo de la 
          biblioteca fisica de la Universidad Mexico Americana del Norte (Uman) en el IX 
          congreso internacional de ciencia, tecnología e innovación.
      - image: assets/img/timeline/carrera.jpg
        title: |
          2024

          **Termino la universidad**
        text: >-
          Concluyen mis estudios universitarios y con ello empieza otras aspiraciones personales...
      - image: assets/img/timeline/xeliger.jpg
        title: |
          2025 - Actualidad

          **Creo el proyecto 'Xeliger'**
        text: >-
          Comienzo mi proyecto personal como parte de mi crecimiento profesional y laboral
  - type: contact.html
    section_id: contacts
    title: Contáctame!!
    text: >-
      Algunos medios en los que puedes contactarme o seguirme son los siguientes, además podrás 
      conocerme mejor como persona
    actions:
    - title: +52 (899) 172-095
      icon: bi-telephone-fill
    - title: Correo electrónico
      icon: bi-envelope-fill
      url: mailto:dcristianeduardo4@gmail.com
    - title: Instagram
      icon: bi-instagram
      url: '#'
    - title: Facebook
      icon: bi-facebook
      url: '#'

---