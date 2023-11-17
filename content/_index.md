---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        Núcleo de
        Psicopatología y Psicología Experimental
      image:
        filename: placalab.jpg
      text: |
        <br>
        
        El **Núcleo de Psicopatología y Psicología Experimental** es una Unidad dedicada al desarrollo de la psicología experimental y el aprendizaje asociativo, tanto para la producción de conocimiento, como para otorgar una sólida formación científica a estudiantes de pregrado y postgrado en psicología y ciencias relacionadas.
  
  - block: markdown
    id: mision
    content:
      title: Nuestra misión
      text: |
        Desarrollar y fomentar la práctica experimental como parte fundamental de la formación del psicólogo, respondiendo a la necesidad de que los estudiantes de la asignatura de Procesos Básicos de Aprendizaje y otros cursos optativos del área, adquieran información teórica y experimental acerca del aprendizaje asociativo y no asociativo.

        Desarrollar la capacidad de analizar, relacionar y comprender los diferentes paradigmas y metodologías del estudio del aprendizaje, así como dar oportunidad a los estudiantes de realizar una investigación enmarcada en los tópicos analizados en cátedra.

        Ampliar el acervo de conocimiento científico acerca del condicionamiento Pavloviano e instrumental, desarrollando investigaciones empíricas que aporten, desde una perspectiva translacional, a la comprensión de fenómenos del comportamiento humano y al desarrollo de intervenciones efectivas.
    design:
      # Choose how many columns the section has. Valid values: '1' or '2'.
      columns: '2'
      
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
      subtitle:
      text: |
        {{% cta cta_link="./equipo/" cta_text="Conócenos →" %}}
    design:
      columns: '1'
---