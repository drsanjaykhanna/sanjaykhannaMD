---
title: ''
date: 2022-10-24
type: landing

design:
  spacing: '6rem'

sections:
  - block: resume-biography-3
    content:
      username: me
      text: ''
    design:
      background:
        gradient_mesh:
          enable: false
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
        I am a **Medical Oncology Registrar** on the UK's first dual-accredited training pathway - the first registrar permitted to combine clinical specialty training with a substantive industry role.

        Over 6 years at **Roche**, I have worked across the pharmaceutical value chain: Medical Affairs, regulatory submissions, clinical development (serving as second-in-command for an **80,000-participant blood-based early detection trial**), and strategic partnering. I spent three years as a portfolio mentor for the Cambridge accelerator **StartCodon**.

        My current **industry-funded MD(Res)** at the Royal Marsden Hospital and Institute of Cancer Research focuses on:
        
        - **U-RESPOND Study**: Qualitative research using choice architecture to understand cancer screening behaviours
        - **Microsimulation Modelling**: Testing population impact of blood-based screening in the UK
        - **LLM-based Decision Support**: Building AI tools for cancer screening designed for equity, scalability, and real-world implementation
        
        I am building the evidence base for evaluating patient-facing AI and continue to publish on **health policy and cancer regulation**.
    design:
      columns: '1'

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

  - block: markdown
    content:
      title: 'Get in Touch'
      text: |-
        I welcome opportunities for collaboration in cancer research, healthcare innovation, AI in medicine, and policy development.
        
        **Email**: [contact@example.com](mailto:contact@example.com)
    design:
      columns: '1'
---
