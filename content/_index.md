---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        NJU AeroSafe Lab
        南京大学航空安全实验室
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        **南京大学航空安全实验室**成立于2025年，致力于航空安全、人工智能与系统可靠性研究的前沿实验室。我们专注于航空器健康管理、故障预测与健康管理(PHM)、人工智能在航空安全中的应用等方向。
        
        <br>
        
        **Nanjing University AeroSafe Laboratory**, founded in 2018, is a leading research lab focusing on aviation safety, artificial intelligence, and system reliability. We specialize in aircraft health management, Prognostics and Health Management (PHM), and AI applications in aviation safety.
  
  - block: collection
    content:
      title: 最新动态 | Latest News
      subtitle:
      text:
      count: 5
      filters:
        author: ''
        category: ''
        exclude_featured: false
        publication_type: ''
        tag: ''
      offset: 0
      order: desc
      page_type: post
    design:
      view: card
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
      title: 最新研究成果 | Latest Research
      text: ""
      count: 5
      filters:
        folders:
          - publication
        publication_type: 'article'
    design:
      view: citation
      columns: '1'

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="认识我们的团队 → Meet the team" %}}
    design:
      columns: '1'
---
