---
title: Home
sections:
- type: heroblock
  template: heroblock
  title: ''
  section_id: hero
  component: hero_block.html
  content: "## A list of independently produced comedy shows in Ottawa maintained
    by [this guy](https://www.instagram.com/lowenergycomic/). "
- type: portfolioblock
  template: portfolioblock
  title: 'Current Shows '
  section_id: latest-projects
  component: portfolio_block.html
  subtitle: ''
  layout_style: tiles
  num_projects_displayed: 4
  view_all_text: 'View All '
  view_all_url: portfolio/index.html
- type: servicesblock
  template: servicesblock
  title: What We Do
  section_id: services
  component: services_block.html
  subtitle: An optional subtitle of the section
  serviceslist:
  - title: Bars || Restaurants
    content: If you are a fan of comedy who has a space that can seat between 10 -
      100 people and interested in supporting live arts feel free to contact us using
      the form
  - title: Apartments || Parties
    content: |-
      ![](/images/8.jpg)

      If you'd like to add comedy to your gathering plans send us a line to learn how it would work
- type: testimonialsblock
  template: testimonialsblock
  title: Testimonials
  section_id: testimonials
  component: testimonials_block.html
  subtitle: An optional subtitle of the section
  testimonialslist:
  - author: John Doe
    avatar: images/john_doe.jpg
    content: Vestibulum a nunc ut eros condimentum posuere. Nullam dapibus quis nunc
      non interdum. Pellentesque tortor ligula, gravida ac commodo eu.
  - author: Jane Roe
    avatar: images/jane_roe.jpg
    content: Sed laoreet magna commodo libero euismod sodales. Nunc ac libero convallis,
      interdum ligula vel, pretium diam. Integer commodo sem at dui sollicitudin,
      vel posuere justo laoreet.
- type: postsblock
  template: postsblock
  title: Latest from the Blog
  section_id: latest-posts
  component: posts_block.html
  subtitle: An optional subtitle of the section
  num_posts_displayed: 2
  actions:
  - label: View Blog
    url: blog/index.html
- type: contactblock
  template: contactblock
  title: Contact Us
  section_id: contact
  component: contact_block.html
  subtitle: An optional subtitle of the section
layout: home
menu:
  main:
    weight: 1

---
