---
layout: home
title: Home
white_header: true
sections:
  - type: hero_section
    section_id: hero_section
    background_image: images/gabriel-forsberg-9sM53e9wTTY-unsplash.jpg
    background_image_opacity: 65
    content: >
      # Changing this title again&#xA;WE USE NO MSG, GMO PRODUCTS. OUR PRODUCE
      ARE MOSTLY ORGANIC.
    actions:
      - title: Order delivery
        url: /store
        arrow: true
        style: primary
      - title: Reservations
        url: '#'
        style: primary
        arrow: false
        type: action
  - type: featured_products_section
    section_id: best_sellers_section
    title: Popular items
    icon: false
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
    title: Testimonials
    testimonials:
      - author:
          name: John Dope
          location: 'Colorado, USA'
        text: >-
          I didn't know the Snipcart guys were into herbs as well! How beautiful
          is that Planty theme. I'm going to launch a killer JAMstack e-commerce
          store using this for sure.
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
  title: Planty Theme
  description: The preview of the Planty theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Planty Theme
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
      value: Planty Theme
    - name: 'twitter:description'
      value: The preview of the Planty theme
    - name: 'twitter:image'
      value: images/header.jpg
      relativeUrl: true
---
