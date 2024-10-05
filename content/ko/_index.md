---
title: 전영상 포트폴리오
date: 2024-10-05
type: landing

sections:
  - block: features
    content:
      profile: true
      image: 
        placement : 1
        focal_point: "Center"
      title: <span style="font-size:90%">안녕하세요!</span>
      text:  <span style="font-size:90%">저는 전북대 컴퓨터공학부에 재학중인 21학번 전영상입니다. 백엔드에 관심이 있어 현재 Springboot 및 JAVA를 공부하고 있습니다.</span>
  
  - block: slider
    content:
      title: <span style="font-size:90%">Stack</span>
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



---

