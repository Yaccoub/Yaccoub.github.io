---
# Leave the homepage title empty to use the site title
title: ''
date: 2026-10-10
type: landing

sections:
  # 1. Hero: who I am, in one screen
  - block: dev-hero
    id: hero
    content:
      username: me
      greeting: ""
      show_status: false
      show_scroll_indicator: false
      typewriter:
        enable: false
      cta_buttons:
        - text: Download Résumé
          url: uploads/Alaeddine-Yacoub-Resume.pdf
          icon: arrow-down-tray
        - text: Get in Touch
          url: "#contact"
          icon: envelope
    design:
      style: centered
      avatar_shape: circle
      animations: false
      background:
        color:
          light: "#ffffff"
      spacing:
        padding: ["2rem", "0", "1.5rem", "0"]

  # 4. Experience & education timeline
  - block: experience
    id: experience
    content:
      title: Experience
      username: me
    design:
      date_format: 'Jan 2006'
      is_education_first: false
      background:
        color:
          light: "#f5f5f7"
      spacing:
        padding: ["1.5rem", "0", "1.5rem", "0"]

  # 5. Publications
  - block: awards
    id: publications
    content:
      title: Publication
      username: me
    design:
      background:
        color:
          light: "#ffffff"
      spacing:
        padding: ["1.5rem", "0", "1.5rem", "0"]

  # 6. Toolbox
  - block: tech-stack
    id: skills
    content:
      title: Toolbox
      subtitle: Tools I have used in production and research.
      categories:
        - name: Product & Delivery
          items:
            - name: Product Ownership
            - name: Roadmap Planning
            - name: Supplier Management
            - name: Budget Management
        - name: AI & Perception
          items:
            - name: VLM Fine-Tuning & Evaluation
            - name: Vector Search
            - name: RAG
            - name: LangGraph
            - name: MCP
            - name: Langfuse
            - name: vLLM
            - name: Physical AI
            - name: Sensor Calibration & Fusion
        - name: Cloud & Engineering
          items:
            - name: Python
              icon: devicon/python
            - name: PyTorch
              icon: devicon/pytorch
            - name: Amazon Bedrock
              icon: hero/sparkles
            - name: Amazon SageMaker
              icon: hero/cpu-chip
            - name: AWS Batch
              icon: hero/server-stack
            - name: Kubernetes
              icon: devicon/kubernetes
            - name: Argo Workflows
              icon: brands/argo
    design:
      style: grid
      show_levels: false
      background:
        color:
          light: "#f5f5f7"
      spacing:
        padding: ["1.5rem", "0", "1.5rem", "0"]

  # 7. Also: workshops, volunteering, open source, languages
  - block: markdown
    id: also
    content:
      title: Also
      text: |-
        - **Workshops** BMW Group, since 2024. AI workshops and hackathons. Co-organized a series on agentic AI workflows for 200+ colleagues.
        - **Volunteering** Instructor, Data Structures and Algorithms, Bavarian Academy for Foreign Trade (2022). Taught 25 participants in a software development retraining course.
        - **Open source** [DIY Smart Microfluidic Pressure Pump](https://github.com/Yaccoub/Smart_Pump), TranslaTUM (2021). A low-cost, pressure-driven pump with a stable flow rate as low as 0.1 µl/min.
        - **Languages** French and Arabic (bilingual) · English and German (proficient) · Spanish (intermediate)
    design:
      background:
        color:
          light: "#ffffff"
      spacing:
        padding: ["1.5rem", "0", "1.5rem", "0"]

  # 8. Contact
  - block: contact-info
    id: contact
    content:
      title: Get in Touch
      autolink: true
    design:
      columns: '1'
      background:
        color:
          light: "#f5f5f7"
      spacing:
        padding: ["1.5rem", "0", "2rem", "0"]
---
