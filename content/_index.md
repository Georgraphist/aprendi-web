---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Laboratorio
        de Psicología Experimental
      image:
        filename: placalab.jpg
      text: |
        <br>
        
        El **Laboratorio de Psicología Experimental: Prof. Ronald Betancourt Mainhard** es una Unidad dedicada al desarrollo de la psicología experimental y el aprendizaje asociativo, tanto para la producción de conocimiento, como para otorgar una sólida formación científica a estudiantes de pregrado y postgrado en psicología y ciencias relacionadas.
  
  - block: markdown
    id: mision
    content:
      title: Nuestra misión
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
      
  - block: collection
    content:
      title: Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
      columns: '1'
  
  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: coders.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
  
  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./equipo/" cta_text="Conócenos →" %}}
    design:
      columns: '1'
---