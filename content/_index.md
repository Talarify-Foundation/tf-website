---
# Leave the homepage title empty to use the site title
title:
date: 2022-10-24
type: landing

sections:
  - block: markdown
    content:
      title: |
        Understanding and addressing skills and knowledge gaps for a stronger future.
          {style="color: #F1F1F1; font-size:7rem;"}
      text: |

    design:
      background:
        color: '#2D3142'
        image:
          # Name of image in `assets/media/`.
          filename: home.svg
          # Apply image filters?
          filters:
            # Darken the image? Range 0-1 where 1 is transparent and 0 is opaque.
            brightness: 0.3
          #  Image fit. Options are `cover` (default), `contain`, or `actual` size.
          size: cover
          # Image focal point. Options include `left`, `center` (default), or `right`.
          position: center
          # Use a fun parallax-like fixed background effect on desktop? true/false
          parallax: true
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true

        
   
  - block: markdown
    content:
      title: At Talarify Foundation we do three things
      subtitle: ''
      text: |
        <br>
        <div class="container">
              <div class="row">
              <div class="col-4">
                  <p align="center">
                    <a href="https://doi.org/10.5281/zenodo.14961866" target="_blank"><img src="../uploads/research.svg" width="70%"></a>
                  </p>
                  <h2 align="center">
                    Scoping Research
                  </h2>
                  <p align="center">
                    Perform research to understand specific teaching and learning needs in niche environments to ensure optimal use of resources and time.
                  </p>
              </div>
              <div class="col-4">
                  <p align="center">
                      <a href="https://doi.org/10.5281/zenodo.14961866" target="_blank"><img src="../uploads/localisation.svg" width="70%"></a>
                  </p>
                  <h2 align="center">
                    Resource Localisation
                  </h2>
                  <p align="center">
                    We support the localisation and contextualisation of learning resources and training interventions to facilitate optimal learning experiences.
                  </p>
              </div>
              <div class="col-4">
                  <p align="center">
                      <a href="https://doi.org/10.5281/zenodo.14961866" target="_blank"><img src="../uploads/community.svg" width="70%"></a>
                  </p>
                  <h2 align="center">
                    Communities of Practice
                  </h2>
                  <p align="center">
                    We enable champions to grow communities of practice where continuous learning and knowledge sharing can thrive.
                  </p>
              </div>
              </div>
              </div>

    design:
      columns: '1'
      background:
        image: 
          filename: 
          filters:
            brightness: 1
          parallax: false
          position: 
          size: 
          text_color_light: true
      spacing:
        padding: ['20px', '0', '20px', '0']
      css_class: fullscreen



  - block: markdown
    content:
      title:
      subtitle:
      text: |
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: '1'
---
