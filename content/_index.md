---
title: 'Home'
date: 2023-10-24
type: landing

design:
  background:
    image:
      # Add your image background to `assets/media/`.
      filename: bg-hue.svg

sections:
  - block: resume-biography
    content:
      # The user's folder name in content/authors/
      username: admin
    design:
      biography:
        style: 'text-align: justify; font-size: 0.8em;'
  - block: cta-button-list
    content:
      # Need a custom icon?
      # Add an SVG image to the `assets/media/icons/` folder and reference it in the `icon` field below
      buttons:
        - text: FedRE
          icon: brands/arxiv
          url: uploads/FedRE.pdf
        - text: Noise Adaptation Framework (NAF)
          icon: brands/arxiv
          url: uploads/NAF.pdf
        - text: NeuralMark
          icon: brands/arxiv
          url: uploads/NeuralMark.pdf
      
        
---
