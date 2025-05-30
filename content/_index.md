---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: hero
    demo: true # Only display this section in the Hugo Blox Builder demo site
    content:
      title: Hugo Academic Theme
      image:
        filename: hero-academic.png
      cta:
        label: '**Get Started**'
        url: https://hugoblox.com/templates/
      cta_alt:
        label: Ask a question
        url: https://discord.gg/z8wNYzb
      cta_note:
        label: >-
          <div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/hugo-blox-builder" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star Hugo Blox Builder</a></div><div style="text-shadow: none;"><a class="github-button" href="https://github.com/HugoBlox/theme-academic-cv" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star">Star the Academic template</a></div>
      text: |-
        **Generated by Hugo Blox Builder - the FREE, Hugo-based open source website builder trusted by 500,000+ sites.**
        **Easily build anything with blocks - no-code required!**
        From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      background:
        gradient_end: '#1976d2'
        gradient_start: '#004ba0'
        text_color_light: true
  - block: about.biography
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
#  - block: skills
#    content:
#      title: Skills
#      text: ''
      # Choose a user to display skills from (a folder name within `content/authors/`)
#      username: admin
#    design:
#      columns: '1'

  - block: markdown
    content:
      title: Recent News
      text: |
          <i class="fa-regular fa-newspaper"></i> &nbsp; **2025.05** &nbsp; Two papers ([Discrete Diffusion](https://arxiv.org/abs/2502.06768), [LoRA theory](https://arxiv.org/abs/2502.09376)) are accepted at ICML 2025, both as spotlight presentations! (Top 2.6%). <br><br>
          <i class="fa-regular fa-newspaper"></i> &nbsp; **2024.09** &nbsp;  I’m starting my Ph.D. at Harvard University, prospectively advised by Prof. [Sitan Chen](https://sitanchen.com/) and [Sham KaKade](https://shamulent.github.io/). I’m really thrilled to pursue my research career at Harvard University! <br><br>
          <i class="fa-regular fa-newspaper"></i> &nbsp; **2024.08** &nbsp; I'm honored to be selected as Ilju Foundation scholarship, which supports graduate students studying abroad. <br><br>
          <i class="fa-regular fa-newspaper"></i> &nbsp; **2024.04** &nbsp; Excited to announce my new paper, [Optimal Acceleration for Minimax and Fixed-Point Problems is Not Unique](https://arxiv.org/abs/2404.13228) (ICML 2024, Spotlight, Top 3.5%). By proposing novel algorithms, we suggested that the optimal acceleration mechanism in minimax optimization and fixed-point problems is not unique. Surprisingly, our new algorithms are **H-dual** to the prior anchor-based accelerated methods: We discover H-duality in another setups! <br><br>
          <i class="fa-regular fa-newspaper"></i> &nbsp; **2023.12** &nbsp; I attended [NeurIPS 2023](https://neurips.cc/Conferences/2023) and gave a poster presentation. <br><br>
    design:
      columns: '1'
  
  - block: experience
    content:
      title: Experience
      # Date format for experience
      #   Refer to https://docs.hugoblox.com/customization/#date-format
      date_format: Jan 2006
      # Experiences.
      #   Add/remove as many `experience` items below as you like.
      #   Required fields are `title`, `company`, and `date_start`.
      #   Leave `date_end` empty if it's your current employer.
      #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
      items:
        - title: Ph.D. Student at Harvard
          company: Under Professor [Sitan Chen](https://sitanchen.com/) and [Sham KaKade](https://shamulent.github.io/)
          company_url: ''
          company_logo: 
          location: 
          date_start: '2024-09-01'
          date_end: ''
          description: Diffusion Models
        - title: Research Intern at MIT
          company: Under Professor [Asuman Ozdaglar](https://scholar.google.com/citations?user=GcuxcLYAAAAJ&hl=en)
          company_url: ''
          company_logo: 
          location: 
          date_start: '2023-07-01'
          date_end: '2023-08-31'
          description: Research on Optimization Theory
        - title: Research Intern at Seoul National University
          company: Under Professor [Ernest Ryu](https://ernestryu.com/)
          company_url: ''
          company_logo: 
          location: 
          date_start: '2022-09-01'
          date_end: '2024-08-31'
          description: Research on Optimization Theory
    design:
      columns: '2'
---
