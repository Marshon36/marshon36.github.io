---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

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
        shape: rounded
  - block: markdown
    content:
      title: 'Research'
      subtitle: ''
      text: |-
        I am a member of the [DAMS](https://dams.ustc.edu.cn/) (Data Mining for Seismology) group at USTC.
        My current work combines geophysical insight with statistical and machine-learning tools to better understand earthquakes and Earth's interior.

        My main interests include seismic source processes, deep Earth structures, and machine learning for seismology.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Selected Publications
      filters:
        folders:
          - publications
      count: 5
    design:
      view: compact
---
