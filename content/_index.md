---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        CV4DT
      image:
        filename: home.png
      text: |
        <br>
        
        The **Computer Vision for Digital Twins (CV4DT)** is a research group based at the [University of Cambridge](https://www.cam.ac.uk/) and led by [Olaf Wysocki](https://olafwysocki.github.io/). The CV4DT centres on developing methods and datasets for pushing the boundaries of 3D computer vision for accurate transfer of reality into the digital world to enable simulation before any action is taken.
  
 #  - block: collection
 #    content:
 #      title: Latest News
 #      subtitle:
 #      text:
 #      count: 5
 #      filters:
 #        author: ''
 #        category: ''
 #        exclude_featured: false
 #        publication_type: ''
 #        tag: ''
 #      offset: 0
 #      order: desc
 #      page_type: post
 #    design:
 #      view: card
 #      columns: '1'
#
 # - block: markdown
 #   content:
 #     title:
 #     subtitle: ''
 #     text:
 #   design:
 #     columns: '1'
 #     background:
 #       image: 
 #         filename: coders.jpg
 #         filters:
 #           brightness: 1
 #         parallax: false
 #         position: center
 #         size: cover
 #         text_color_light: true
 #     spacing:
 #       padding: ['20px', '0', '20px', '0']
 #     css_class: fullscreen

  - block: slider
    content:
      slides:
      - title: 👋 Welcome to the CV4DT world
        content: 'Check out our research focus...'
        align: center
        background:
          image:
            filename: zahaAnimated.gif
            filters:
              brightness: 0.7
          position: right
          color: '#666'
        link:
          icon: graduation-cap
          icon_pack: fas
          text: Join Us
          url: ../contact/
      - title: 3D Semantic Understanding
        content: '3D scene understanding with imbalanced data'
        align: left
        background:
          image:
            filename: zahaAnimated.gif
            filters:
              brightness: 0.7
          position: center
          color: '#555'
      - title: 3D Semantic Object Reconstruction
        content: 'Reconstructing high-detail semantic 3D models'
        align: left
        background:
          image:
            filename: relod3.jpg
            filters:
              brightness: 0.5
          position: center
          color: '#333'
      - title: 3D Models as Novel Modality
        content: 'High-detail structured 3D models as new sensor signal'
        align: left
        background:
          image:
            filename: pose.jpg
            filters:
              brightness: 0.7
          position: center
          color: '#555'
    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: ''
      is_fullscreen: true
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 2200

  - block: collection
    content:
      title: Latest Papers
      text: ""
      count: 5
      filters:
        folders:
          - publication
   #       publication_type: 'article'
    design:
      view: citation
      columns: '1'

#  - block: markdown
#    content:
#      title:
#      subtitle:
#      text: |
#        {{% cta cta_link="./contact/" cta_text="Contact us →" %}}
#    design:
#      columns: '1'
#      background:
#        image: 
#          filename: ingolstadt.jpg
#          filters:
#            brightness: 0.5
#          parallax: false
#          position: center
#          size: cover
#          text_color_light: true
#      spacing:
#        padding: ['200px', '0', '2px', '0']
#      css_class: fullscreen
---
