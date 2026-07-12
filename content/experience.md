---
title: 'CV'
date: 2023-10-24
type: landing

design:
  spacing: '5rem'

# Note: `username` refers to the user's folder name in `content/authors/`

# Page sections
sections:
  - block: resume-experience
    content:
      username: me
    design:
      date_format: 'January 2006'
      is_education_first: true
  - block: resume-skills
    content:
      title: Skills
      username: me
  - block: resume-awards
    content:
      title: Awards & Honors
      username: me
  - block: resume-languages
    content:
      title: Languages
      username: me
  - block: collection
    content:
      title: Publications
      filters:
        folders:
          - publications
    design:
      view: citation
---
