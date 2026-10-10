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
        padding: ["3.5rem", "0", "2.5rem", "0"]

  # 3. What I do
  - block: features
    id: about
    content:
      title: What I Do
      text: I work where autonomous driving engineering meets product delivery.
      items:
        - name: Product Ownership
          icon: presentation-chart-line
          description: Turning stakeholder needs into requirements, priorities and a shared roadmap across BMW teams and external partners in three countries, including partner budget and procurement.
        - name: AI & Data Engineering
          icon: cpu-chip
          description: Vision-language models, multimodal embeddings and vector search that make fleet driving data searchable and model-ready, from ground-truth pipelines to scenario discovery.
        - name: Enablement
          icon: user-group
          description: Hands-on AI workshops and hackathons on agentic workflows for 200+ colleagues, and teaching data structures and algorithms.
    design:
      background:
        color:
          light: "#ffffff"
      spacing:
        padding: ["3rem", "0", "3rem", "0"]

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
        padding: ["3rem", "0", "3rem", "0"]

  # 5. Publications
  - block: awards
    id: publications
    content:
      title: Publications
      username: me
    design:
      background:
        color:
          light: "#ffffff"
      spacing:
        padding: ["3rem", "0", "3rem", "0"]

  # 6. Toolbox
  - block: tech-stack
    id: skills
    content:
      title: Toolbox
      subtitle: Tools I have used in production and research.
      categories:
        - name: Languages
          items:
            - name: Python
              icon: devicon/python
            - name: C++
              icon: devicon/cplusplus
            - name: SQL
              icon: devicon/postgresql
        - name: Cloud & Pipelines
          items:
            - name: AWS
              icon: devicon/amazonwebservices
            - name: Kubernetes
              icon: devicon/kubernetes
            - name: Argo Workflows
              icon: devicon/argocd
            - name: Docker
              icon: devicon/docker
        - name: AI & Perception
          items:
            - name: PyTorch
              icon: devicon/pytorch
            - name: TensorFlow
              icon: devicon/tensorflow
            - name: OpenCV
              icon: devicon/opencv
            - name: ROS
              icon: devicon/ros
    design:
      style: grid
      show_levels: false
      background:
        color:
          light: "#f5f5f7"
      spacing:
        padding: ["3rem", "0", "3rem", "0"]

  # 7. Teaching and languages (one compact section)
  - block: markdown
    id: more
    content:
      title: Teaching & Languages
      text: |-
        **Workshops & Teaching**
        - AI workshops and hackathons, BMW Group (since 2024): co-organized a cross-departmental series for 200+ employees on building and applying agentic AI workflows.
        - Data Structures and Algorithms, Bavarian Academy for Foreign Trade (2022): taught 25 participants in a software development vocational retraining course.


        **Languages**
        - French and Arabic (bilingual) · English and German (proficient) · Spanish (intermediate)
    design:
      background:
        color:
          light: "#ffffff"
      spacing:
        padding: ["3rem", "0", "3rem", "0"]

  # 8. Contact
  - block: contact-info
    id: contact
    content:
      title: Get in Touch
      text: |-
        I'm happy to talk about autonomous driving data, AI and product delivery.
      email: yaccoubala@gmail.com
      autolink: true
    design:
      columns: '1'
      background:
        color:
          light: "#f5f5f7"
      spacing:
        padding: ["3rem", "0", "4rem", "0"]
---
