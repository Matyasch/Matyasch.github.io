---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: About
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: publications
    content:
      title: Publications
      filters:
        folders:
          - publication
    design:
      columns: '2'
      view: citation
  - block: experience
    id: timeline
    content:
      title: Timeline
      # Date format for experience
      #   Refer to https://wowchemy.com/docs/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: PhD Candidate
          company: University of Amsterdam
          company_logo: uva
          location: Amsterdam
          date_start: '2023-01-01'
          date_end: ''
          description: Currently, I am a PhD Candidate in causality-inspired ML/RL.
        - title: Teaching Assistant
          company: University of Amsterdam
          company_logo: uva
          location: Amsterdam
          date_start: '2021-10-01'
          date_end: '2022-02-01'
          description: I was a teaching assistant for the Natural Language Processing 1 course. My responsibilities included running the lab sessions, and grading assignments and exams.
        - title: Master of Science
          company: University of Amsterdam
          company_logo: uva
          location: Amsterdam
          date_start: '2020-09-01'
          date_end: '2022-12-01'
          description: I finished the Artificial Intelligence MSc programme where I got familiar with machine learning and causality. My thesis investigated long-term credit assignment in reinforcement learning.
        - title: Software Developer
          company: Ericsson
          company_logo: ericsson
          location: Budapest
          date_start: '2019-06-01'
          date_end: '2020-08-01'
          description: As part of a continuous integration and continuous delivery team, my responsibilities included managing developer environments, test and build pipelines, and developing a deployment software for complex cloud-based applications.
        - title: Erasmus Exchange Student
          company: Vrije Universiteit Amsterdam
          company_logo: vu
          location: Amsterdam
          date_start: '2018-09-01'
          date_end: '2019-02-01'
          description: Spent a semester as an Erasmus student at VU. I worked with students from all backgrounds ad used english in my studies and also in my everyday life during my whole stay.
        - title: Bachelor of Science
          company: Eötvös Loránd University
          company_logo: elte
          location: Budapest
          date_start: '2016-09-01'
          date_end: '2020-07-01'
          description: I finished the Computer Science BSc programme where I specialized in software design and algorithm correctness. For my thesis project I developed an interactive GUI for the trace module of the BPF Compiler Collection.
    design:
      columns: '2'
---
