---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2022-10-24
type: landing

design:
  # Default section spacing
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/resume.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '� My Research'
      subtitle: ''
      text: |-
        I am a **Medical Oncology Registrar** on the UK's first dual-accredited training pathway—the first registrar permitted to combine clinical specialty training with a substantive industry role.

        Over 6 years at **Roche**, I have worked across the pharmaceutical value chain: Medical Affairs, regulatory submissions, clinical development (serving as second-in-command for an **80,000-participant blood-based early detection trial**), and strategic partnering. I spent three years as a portfolio mentor for the Cambridge accelerator **StartCodon**.

        My current **industry-funded MD(Res)** at the Royal Marsden Hospital and Institute of Cancer Research focuses on:
        
        - **U-RESPOND Study**: Qualitative research using choice architecture to understand cancer screening behaviours
        - **Microsimulation Modelling**: Testing population impact of blood-based screening in the UK
        - **LLM-based Decision Support**: Building AI tools for cancer screening—designed for equity, scalability, and real-world implementation
        
        I am building the evidence base for evaluating patient-facing AI and continue to publish on **health policy and cancer regulation**.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 2
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
    design:
      view: citation
  - block: collection
    id: projects
    content:
      title: Research Projects
      filters:
        folders:
          - projects
    design:
      view: article-grid
      columns: 3
  - block: cta-card
    content:
      title: Get in Touch
      text: |-
        I welcome opportunities for collaboration in cancer research, healthcare innovation, 
        AI in medicine, and policy development.
      button:
        text: Contact Me
        url: "mailto:contact@example.com"
    design:
      card:
        # Card background color (CSS class)
        css_class: 'bg-primary-300 dark:bg-primary-700'
        css_style: ''
---
