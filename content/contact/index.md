---
title: Contact
date: 2022-10-24

type: landing

sections:
  - block: contact
    content:
      title: Contact
      text: Feel free to send us an email, if you are interested in collaboration or joining our group as
        - intern
        - visiting researcher
        - PhD candidate
        - Post-doc
      email: okw24@cam.ac.uk
      address:
        street: 7a JJ Thomson Ave,  
        city: Cambridge
        region: Cambridgeshire
        postcode: 'CB3 0FA'
        country: United Kingdom
        country_code: UK
      coordinates:
        latitude: '52.2106', 
        longitude: '0.0944',
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

  - block: markdown
    content:
      title:
      subtitle: ''
      text:
    design:
      columns: '1'
      background:
        image: 
          filename: contact.jpg
          filters:
            brightness: 1
          parallax: false
          position: center
          size: cover
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen
---
