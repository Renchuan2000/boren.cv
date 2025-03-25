---
title: "Deep Constrained Clustering with Active Learning"
authors:
  - admin
  - Robert Ford
author_notes:
  - "Equal contribution"
  - "Equal contribution"
date: "2023-09-29T00:00:00Z"
doi: "doi.org/10.1142/S0218001424540132"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-29T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: 
  - "article-journal"

# Publication name and optional abbreviated publication name.
publication: "*Journal of Source Themes, 1*(1)"
publication_short: ""

abstract: |
  Deep semi-supervised clustering approaches, which use supervised data to help the deep neural network acquire
  cluster-friendly representations, have improved clustering performance and simultaneously increased the semantic value of
  the clustering results. However, the majority of them cannot utilize both labeled and unlabeled data completely. Furthermore,
  in these methods, the supervised information is either passively acquired or randomly picked, which may be insufficient,
  redundant, and even decrease the performance of these models. This paper provides a deep semi-supervised clustering
  technique with active learning to address the problems mentioned above. The procedure is divided into two sections: model
  training and data labeling. In the model training section, the paired data is used to train the pseudo-Siamese network, and
  then the sub networks of the pseudo-Siamese network are fine-tuned using self-training. A new query strategy is devised in
  the data labeling part, which combines the traditional uncertainty query strategy with the deep Bayesian uncertainty query
  strategy. Finally, substantial tests are conducted to confirm the utility of the suggested approach on certain real-world data
  sets. The resultts of the tests demonstrate that both the suggested method and query strategy are practical.

# Summary. An optional shortened abstract.
summary: This paper presents a novel deep semi-supervised clustering method with active learning, enhancing clustering performance by handling complex constraints and improving efficiency through active learning strategies.
tags:
- Deep Learning
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://journals.indexcopernicus.com/api/file/viewByFileId/1843643
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: ''
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: ''
# url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Deep Constrained Clustering with Active Learning'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
