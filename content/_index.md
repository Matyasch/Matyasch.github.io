---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "4rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: short
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
  - block: collection
    id: news
    content:
      title: Recent News
      filters:
        folders:
          - news
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
    design:
      view: citation
  - block: experience
    id: timeline
    content:
      username: admin
    design:
      columns: 2
      css_style: "padding-bottom:10rem"
---
