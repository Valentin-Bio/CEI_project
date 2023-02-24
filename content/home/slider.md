---
widget: slider  # Use the Slider widget as this page section
weight: 10  # Position of this section on the page
active: false  # Publish this section?
headless: true  # This file represents a page section.

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title:  Welcome to the CIE 
      content: Take a look at what we're working on...
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: avatar.jpeg
        fit: cover
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Research lines
        url: ./../project
    
    - title: Meet the CIE!
      content: 
      align: left
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: avatar.jpeg
        fit: cover
      link:
        icon: graduation-cap
        icon_pack: fas
        text: Members
        url: ./../members
---