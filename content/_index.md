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
        Research Group
      image:
        filename: home.png
      text: |
        <br>
        
        The **Computer Vision for Digital Twins (CV4DT)** research group based at the [University of Cambridge](https://www.cam.ac.uk/) and led by [Olaf Wysocki](https://olafwysocki.github.io/) centres on developing methods and datasets for pushing the boundaries of 3D computer vision for accurate transfer of reality into the digital world to enable prediction before any action is taken.g
  
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

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./contact/" cta_text="Contact us →" %}}
    design:
      columns: '1'
---
