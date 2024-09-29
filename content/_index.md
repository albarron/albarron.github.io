---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: resume-biography
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
      text:
    design:
      css_class: dark
      background:
        color: black
        image:
          # Add your image background to `assets/media/`.
          filename: li-yang-5h_dMuX_7RE-unsplash.webp
          filters:
            brightness: 0.4
          size: cover
          position: center
          parallax: false
  - block: stats
    content:
      items:
        - statistic: "??"
          description: |
            Publications
        - statistic: "??"
          description: |
            Citations
        - statistic: "??"
          description: |
            h-index
    design:
      # Section background color (CSS class)
      css_class: "bg-gray-100 dark:bg-gray-900"
      # Reduce spacing
      spacing:
        padding: [0, 0, 0, 0]
  - block: markdown
    content:
      title: '📚 My Research'
      subtitle: ''
      text: |-
        I am an Associate Professor at Università di Bologna. My main mission is bringing (real) computing to the Department of Interpreting and Translation.

        I research on the analysis and identification of harming contents online (from hate speech to propaganda and disinformation), I also play with NLP for Gastronomy and laterly I am engaged with varieties of languages.
        
        Do not hesitate to reach out 😃
    design:
      columns: '1'
  - block: collection
    content:
      title: Recent News
      subtitle: ''
      text: ''
      # Page type to display. E.g. post, talk, publication...
      page_type: post
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
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

  - block: people
    content:
      title: Meet the Team
      # Choose which groups/teams of users to display.
      #   Edit `user_groups` in each user's profile to add them to one or more of these groups.
       # text: "Meet the team"
      user_groups:
          - Associate Professors
          - Researchers
          - PhD Students
          - Alumni
          # - Grad Students
          # - Administration
          # - Visitors
          
      sort_by: Params.last_name
      sort_ascending: true
    design:
      show_interests: false
      show_role: true
      show_social: true
---
