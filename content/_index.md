---
# Leave the homepage title empty to use the site title
title:
date: 2025-04-29
type: landing

sections:
  - block: hero
    content:
      title: |
        ZG Research Group
      image:
        filename: welcome.jpg
      text: |
        <br>
        
        本小组主要采用土壤理化分析、微生物高通量测序和土壤动物鉴定等方法，结合数据统计分析，研究喀斯特生境下石漠化、生态恢复对土壤碳周转、微生物和动物的群落结构和多样性的影响，从2017年由一个人逐渐增加到1个导师+4个硕士研究生的小组结构。
  
  - block: collection
    content:
      title: Latest News
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
      title: Latest Preprints
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
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
