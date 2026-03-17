---
title: ''
summary: ''
date: 2024-01-01
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      background:
        gradient_mesh:
          enable: true
      name:
        size: md
      avatar:
        size: medium
        shape: circle
  - block: markdown
    content:
      title: 'My Research'
      subtitle: ''
      text: |-
        I am a senior undergraduate in Physics at Seoul National University, focusing on **stellarator plasma optimization**.

        My research interests include plasma confinement, magnetic field optimization, and computational methods for fusion energy devices.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Publications
      filters:
        folders:
          - publications
        featured_only: false
    design:
      view: citation
  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 2
  - block: collection
    id: blog
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      page_type: blog
      count: 5
      filters:
        author: ''
        category: ''
        tag: ''
        exclude_featured: false
        exclude_future: false
        exclude_past: false
      order: desc
    design:
      view: card
  - block: markdown
    id: contact
    content:
      title: Contact
      subtitle: ''
      text: |-
        Feel free to reach out via email at [gojonghyeon0301@gmail.com](mailto:gojonghyeon0301@gmail.com) or connect with me on [GitHub](https://github.com/rhwhdgus).
    design:
      columns: '1'
---
