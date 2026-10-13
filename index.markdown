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
      - title: Project 1
        text: This is a very short project description.
        # the images are located in:
        # img/portfolio/fullsize
        # img/portfolio/thumbnails
        icon: 1.jpg
        url: '#'
      - title: Project 2
        text: This is a very short project description.
        icon: 2.jpg
        url: '#'
      - title: Project 3
        text: This is a very short project description.
        icon: 3.jpg
        url: '#'
      - title: Project 4
        text: This is a very short project description.
        icon: 4.jpg
        url: '#'
      - title: Project 5
        text: This is a very short project description.
        icon: 5.jpg
        url: '#'
      - title: Project 6
        text: This is a very short project description.
        icon: 6.jpg
        url: '#'

  - type: aside.html
    section_id: aside
    title: Mis Proyectos
    actions:
      - title: Repositorio - GitHub
        url: https://startbootstrap.com/themes/creative/
        class: btn-light

  - type: members.html
    section_id: members
    title: Our Crew!
    background_style: bg-info text-white
    members:
      - title: Christina M. Aponte
        text: Singer and Songwriter
        image: assets/img/members/person1.jpg
        url: '#'
      - title: Gary D. Stevens
        text: Bass guitar.
        image: assets/img/members/person2.jpg
        url: '#'
      - title: Devon J. Fletcher
        text: Lead guitar.
        image: assets/img/members/person3.jpg
        url: '#'
      - title: Todd E. Anderson
        text: Drums, percussion.
        image: assets/img/members/person5.jpg
        url: '#'
      - title: Daniel T. Riley
        text: Musician, songwriter, producer.
        image: assets/img/members/person6.jpg
        url: '#'
      - title: Ella P. Walter
        text: PR.
        image: assets/img/members/person7.jpg
        url: '#'

  - type: timeline.html
    section_id: timeline
    title: Major Achievements!
    background_style: bg-dark text-primary
    last_image: assets/img/timeline-end.png
    actions:
      - image: assets/img/portfolio/thumbnails/1.jpg
        title: >+
          2017-2018
          **Humble Beginnings**
        text: >-
          We begun with small group of people willing to work hard and make our
          teaching skills worth , in front of all others!
      - image: assets/img/portfolio/thumbnails/2.jpg
        title: >+
          November 2019
          An Coaching started
        text: >-
          We started to gather like minded people and started our stategies
          and future plans to them. As a result , interested people joined us!

  - type: contact.html
    section_id: contacts
    title: Contáctame!!
    text: >-
      Ready to start your next project with us? Give us a call or send us an email
      and we will get back to you as soon as possible!
    actions:
    - title: +1 (202) 555-014
      icon: bi-telephone-fill
    - title: E-Mail
      icon: bi-envelope-fill
      url: mailto:contact@yourwebsite.com
    - title: Twitter
      icon: bi-twitter
      url: '#'
    - title: Facebook
      icon: bi-facebook
      url: '#'

---