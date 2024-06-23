---
# Leave the homepage title empty to use the site title
title: ""
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: "6rem"

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text: ""
      # Show a call-to-action button under your biography? (optional)
      # button:
      #   text: Download CV
      #   url: uploads/resume.pdf
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: stacked-peaks.svg
          filters:
            brightness: 1.0
          size: cover
          position: center
          parallax: false
  # - block: markdown
  #   content:
  #     title: '📌 Open Positions'
  #     subtitle: ''
  #     text: |
  #      I am seeking an enthusiastic and dedicated doctoral (PhD) student interested in specializing in Ocean Mobility Data Mining within the Artificial Intelligence and Machine Learning cluster of the Faculty of Computer Science at Dalhousie University. This exciting opportunity offers full funding and enrollment in the Computer Science Graduate Program in Halifax - NS, Canada. The successful candidates will have the unique chance to immerse themselves in a dynamic and research-rich environment where they can learn, collaborate, and contribute to cutting-edge developments in this field.

  #      Details on this offer are in the PDF attached to this email or in the following link: https://drive.google.com/file/d/1opH51kCLzzvPjfHAj8-ZBKlKjHedOa6d
  #   design:
  #     columns: '2'
  - block: collection
    id: publications
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: news
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 3
      # Filter on criteria
      filters:
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: date-title-summary
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
---