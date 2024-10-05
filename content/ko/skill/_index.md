---
title: Skills
date: 2022-10-24

type: landing

sections:
  - block: collection
    content:
      id: skills
      title: Skills
      count: 2  # 카드 수를 제한
      filters:
        tag: 'skills'
    design:
      view: community/custom_card
      columns: '2'
  
  # 자바 스킬 카드
  - block: features
    content:
      title: <span style="font-size: 90%">Java</span>
      text: <span style="font-size: 80%">Java는 플랫폼 독립적인 프로그래밍 언어로, 다양한 어플리케이션에서 사용됩니다.</span>
      image:
        filename: java.jpg  # 자바 관련 이미지 파일 이름
        placement: 1
        focal_point: "Center"
      icon: java
    design:
      columns: '1'

  # 파이썬 스킬 카드
  - block: features
    content:
      title: <span style="font-size: 90%">Python</span>
      text: <span style="font-size: 80%">Python은 읽기 쉬운 문법과 다양한 라이브러리로 유명한 프로그래밍 언어입니다.</span>
      image:
        filename: python.jpg  # 파이썬 관련 이미지 파일 이름
        placement: 1
        focal_point: "Center"
      icon: python
    design:
      columns: '1'
---
