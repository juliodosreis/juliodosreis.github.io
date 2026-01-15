---
# Leave the homepage title empty to use the site title
title: ""
date: 2026-01-12
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
  - block: markdown
    content:
      title: '📚 About my Research'
      subtitle: ''
      text: |-
        My research agenda centers on investigating and developing methods and technologies for knowledge representation, semantic data management, and intelligent, human-centered systems. I have made sustained contributions to ontology engineering, knowledge graphs, Semantic Web technologies, and natural language processing, with particular emphasis on the evolution, alignment, and validation of dynamic knowledge structures. More recently, my investigations have expanded to include generative and agentic artificial intelligence, exploring the integration of language models with symbolic representations to support explainable, context-aware intelligent systems.

        A distinctive aspect of my research is its interdisciplinary nature. A central focus of my studies is agent-based architectures grounded in large language models (LLM agents). I have investigated how generative models can be embedded in autonomous and collaborative agents that perceive, reason, plan, and make decisions in complex, dynamic environments. My work explores hybrid approaches that combine symbolic knowledge representations — such as ontologies and knowledge graphs — with LLM-driven agents to enable explainability, adaptability, and contextual awareness. These contributions address challenges related to agent cognition, orchestration, planning, memory, and reflection. In this context, my research addresses concerns regarding human, ethical, social, economic, and governance issues. 

        My investigations have been applied to real-world scenarios, including education (teaching and learning systems), industrial process monitoring, e-commerce, and decision-support systems, advancing the state of the art in agentic AI while reinforcing principles of transparency, robustness, and human-centered design. My research has been validated through publications in high-impact international journals and conferences, as well as through multiple national and international awards.

        I have coordinated and participated in several competitive research projects funded by public agencies and industry partners, fostering technology transfer and real-world impact in distinct domains. I actively supervise graduate and undergraduate researchers, helping develop highly qualified professionals and strengthen collaborative research networks at both national and international levels.
    design:
      columns: '1'
  - block: collection
    content:
      title: Recent Publications
      text: ""
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: resume-awards
    content:
      title: Awards
      username: admin
---
