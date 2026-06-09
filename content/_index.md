---
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: admin
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      css_class: hbx-bg-gradient
      avatar:
        size: medium
        shape: circle

  - block: markdown
    content:
      title: 'Research Interests'
      subtitle: ''
      text: |-
        I am interested in statistical machine learning, high-dimensional statistics, reinforcement learning, and the interaction between large language models and statistical methodology. 

        My current goal is to strengthen my theoretical foundation in statistics while gaining more hands-on research experience through course projects, independent study, and research training.
    design:
      columns: '1'

  - block: collection
    id: projects
    content:
      title: Selected Projects
      text: ''
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 2
      fill_image: false
      show_date: false
      show_read_time: false
      show_read_more: true
---
