---
title: Contacto
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contacto
      text: |-
        Lorem ipsum dolor sit amet, consectetur adipiscing elit. Integer tempus augue non tempor egestas. Proin nisl nunc, dignissim in accumsan dapibus, auctor ullamcorper neque. Quisque at elit felis. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia curae; Aenean eget elementum odio. Cras interdum eget risus sit amet aliquet. In volutpat, nisl ut fringilla dignissim, arcu nisl suscipit ante, at accumsan sapien nisl eu eros.
      email: test@exampletest.org
      phone: 888 888 88 88
      address:
        street: Av. Ignacio Carrera Pinto 1045
        city: Ñuñoa
        region: Santiago
        country: Chile
        country_code: es-CL
      coordinates:
        latitude: '-33.46764892345904'
        longitude: '-70.59431530229247'
      directions: Ingresar al edificio de la Facultad de Ciencias Sociales y subir al piso 4
      office_hours:
        - 'Monday 10:00 to 13:00'
        - 'Wednesday 09:00 to 10:00'
      appointment_url: 'https://calendly.com'
      #contact_links:
      #  - icon: comments
      #    icon_pack: fas
      #    name: Discuss on Forum
      #    link: 'https://discourse.gohugo.io'
    
      # Automatically link email and phone or display as text?
      autolink: true
    
      # Email form provider
      form:
        provider: netlify
        formspree:
          id:
        netlify:
          # Enable CAPTCHA challenge to reduce spam?
          captcha: false
    design:
      columns: '1'
