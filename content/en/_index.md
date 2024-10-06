---
title: Jeon Young Sang Portfolio
date: 2024-10-05
type: landing

sections:
  - block: features
    content:
      profile: true
      image: 
        placement : 1
        focal_point: "Center"
      title: <span style="font-size:90%">Hello!</span>
      text:  <span style="font-size:90%">I am a 21st year student at Chonbuk National University, majoring in Computer Science. I am interested in backend and currently studying Springboot and JAVA.</span>
  
  - block: slider
    content:
      title: <span style="font-size:90%">Skills</span>
      slides:
      - title: <span style="font-size:70%">JAVA</span>
        align: center
        background:
          image:
            filename: java.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">Python</span>
        align: center
        background:
          image:
            filename: python.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'
          
      
      - title: <span style="font-size:70%">Spring boot</span>
        align: center
        background:
          image:
            filename: springboot.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">C#</span>
        align: center
        background:
          image:
            filename: csharp.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">C++</span>
        align: center
        background:
          image:
            filename: cpp.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

      - title: <span style="font-size:70%">React</span>
        align: center
        background:
          image:
            filename: react.jpg
            filters:
              brightness: 0.4
          position: center
          color: '#000'

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: '350px'
      slide_width: '100px'
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000




  - block: collection
    content:
      id: section-1
      title: Backend
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        tag: 'BE'
    design:
      view: community/custom_compact
      columns: '1'
  
  - block: collection
    content:
      id: section-2
      title: Game
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        tag: 'GAME'
    design:
      view: community/custom_card
      columns: '1'

  - block: collection
    content:
      id: section-3
      title: Paintings
      subtitle:
      text:
      count: 3
      offset: 0
      order: desc
      filters:
        tag: 'PAINTING'
    design:
      view: community/custom_card
      columns: '1'

---

