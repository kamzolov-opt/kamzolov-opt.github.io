---
# Leave the homepage title empty to use the site title
title: ""
date: 2024-10-22
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
      button:
        text: Download CV
        url: uploads/cv.pdf
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
          
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - papers
        featured_only: true
    design:
      view: article-grid
      columns: 2
  
---
