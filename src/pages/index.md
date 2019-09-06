---
title: Home
sections:
  - component: HeroBlock
    content: >-
      This section can contain a subtitle or tagline. The recommended length is
      one to three sentences, but can be changed as you prefer.
    section_id: hero
    title: Naše putovanje Evropom
    type: heroblock
  - component: ServicesBlock
    section_id: put
    serviceslist:
      - content: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
          ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
          fringilla, fringilla tortor at, pulvinar orci.
        title: Banja Luka
      - content: >-
          Donec lobortis velit sed suscipit lobortis. Ut non quam metus. Nullam
          a maximus mi. Quisque justo nunc, sollicitudin euismod euismod at,
          tincidunt ut tellus. Vivamus rhoncus mattis varius. 
        title: Berlin
      - content: >-
          Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis
          nunc non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
        title: Talin
      - content: >-
          Aliquam pulvinar, orci ac scelerisque tempus, felis leo sagittis
          justo, sit amet condimentum lorem nibh vel quam. Duis consectetur
          lorem ipsum, non efficitur urna viverra et.
        title: Riga
      - content: fgdffg
        title: Vilnius
      - content: fgdg
        title: Beč
    subtitle: An optional subtitle of the section
    title: Put
    type: servicesblock
  - actions:
      - label: View Blog
        url: blog/index.html
    component: PostsBlock
    num_posts_displayed: 2
    section_id: latest-posts
    subtitle: An optional subtitle of the section
    title: Latest from the Blog
    type: postsblock
  - component: TestimonialsBlock
    section_id: putnici
    subtitle: An optional subtitle of the section
    testimonialslist:
      - author: Eldin Zaimović
        avatar: /images/slika.jpg
        content: >-
          Putovanja vas prvo ostave bez riječi, a onda vas pretvore u
          pripovjedača.
      - author: Nerma Bašić
        avatar: /images/nerma.jpg
        content: Oni koji se ne kreću – ne primećuju svoje okove.
    title: Putnici
    type: testimonialsblock
menus:
  main:
    title: Home
    weight: 1
template: home
---

