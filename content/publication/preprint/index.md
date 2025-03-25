---
title: "LL-Diff: Low-light image enhancement utilizing Langevin sampling diffusion"
authors:
- admin
date: "2023-11-25T00:00:00Z"
doi: "doi.org/10.1142/S0218001424540132"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-11-25T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "International Journal of Pattern Recognition and Artificial Intelligence"
publication_short: "IJPRAI"

abstract: In this paper, we propose a new algorithm called LL-Diff, which is innovative compared to traditional augmentation methods in that it introduces the sampling method of Langevin dynamics. This sampling approach simulates the motion of particles in complex environments and can better handle noise and details in low-light conditions. We also incorporate a causal attention mechanism to achieve causality and address the issue of confounding effects. This attention mechanism enables us to better capture local information while avoiding over-enhancement. We have conducted experiments on the LOL-V1 and LOL-V2 datasets, and the results show that LL-Diff significantly improves computational speed and several evaluation metrics, demonstrating the superiority and effectiveness of our method for low-light image enhancement tasks. The code will be released on GitHub when the paper has been accepted.

# Summary. An optional shortened abstract.
summary: This paper proposes LL-Diff, a novel low-light image enhancement method that leverages Langevin sampling diffusion to enhance image brightness and detail while suppressing noise.

tags:
- Image Processing

featured: true

links:
- name: Custom Link
  url: http://example.org
url_pdf: https://www.worldscientific.com/doi/10.1142/S0218001424540132?srsltid=AfmBOor11TsHHdlwEkTf4ogQoPeTg0hUoVSBi167sEypqCXeLdbxkf35
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'LL-Diff: Low-light image enhancement utilizing Langevin sampling diffusion'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- image-processing

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

This work is driven by the results in my [previous paper](/publication/) on Image processing.

<!-- 
Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
