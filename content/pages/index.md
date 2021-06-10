---
layout: home
title: Home
white_header: true
sections:
  - type: hero_section
    section_id: hero_section
    background_image: images/karsten-winegeart-tIWBJN8t7zE-unsplash.jpg
    background_image_opacity: 65
    content: >
      # Los Cachorros


      Todas las marcas de alimentos y alimentos premium para tus mascotas a los
      mejores precios.
    actions:
      - title: CATÁLOGO
        url: /store
        arrow: true
        style: primary
  - type: featured_products_section
    section_id: best_sellers_section
    title: MÁS VENDIDO
    icon: true
    light_title: true
    featured_products:
      - content/pages/products/plant1.md
      - content/pages/products/plant3.md
      - content/pages/products/plant5.md
      - content/pages/products/plant7.md
  - type: featured_categories_section
    section_id: featured_categories_section
    featured_categories:
      - content/pages/category/bigplants.md
      - content/pages/category/cactuses.md
  - type: testimonials_section
    section_id: testimonials_section
    title: RESEÑAS
    testimonials:
      - author:
          name: John Dope
          location: 'Colorado, USA'
        text: >-
          Antes no compraba bultos pequeños de alimento para mi perrito pero se
          terminaban pronto, ahora pido bultos de comida más grandes y me rinden
          mucho más tiempo.
      - author:
          name: Major Payne
          location: 'VA, USA'
        text: >-
          Well I'll be d*mned. These plants really ARE greener than any of my
          recruits.
  - type: promotion_section
    section_id: promotion_section
    title: A new home interior for summer
    subtitle: from $149.99
    image: images/promo.jpg
    background_image: images/leaf.svg
    cta:
      title: Discover
      url: /store
      style: secondary
      arrow: true
seo:
  title: Los Cachorros
  description: The preview of the Planty theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Los Cachorros
      keyName: property
    - name: 'og:description'
      value: The preview of the Planty theme
      keyName: property
    - name: 'og:image'
      value: images/header.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Los Cachorros
    - name: 'twitter:description'
      value: The preview of the Planty theme
    - name: 'twitter:image'
      value: images/header.jpg
      relativeUrl: true
---
