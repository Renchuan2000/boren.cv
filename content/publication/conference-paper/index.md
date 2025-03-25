---
title: 'Deep Constrained Clustering with Active Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Robert Ford

# Author notes (optional)
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'

date: '2023-09-01T00:00:00Z'
doi: 'doi.org/10.1142/S0218001424540132'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-09-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-journal']

# Publication name and optional abbreviated publication name.
publication: In *Studies in Informatics and Control*
publication_short: In *SIC*

abstract: Deep semi-supervised clustering approaches, which use supervised data to help the deep neural network acquire
cluster-friendly representations, have improved clustering performance and simultaneously increased the semantic value of
the clustering results. However, the majority of them cannot utilize both labeled and unlabeled data completely. Furthermore,
in these methods, the supervised information is either passively acquired or randomly picked, which may be insufficient,
redundant, and even decrease the performance of these models. This paper provides a deep semi-supervised clustering
technique with active learning to address the problems mentioned above. The procedure is divided into two sections: model
training and data labeling. In the model training section, the paired data is used to train the pseudo-Siamese network, and
then the sub networks of the pseudo-Siamese network are fine-tuned using self-training. A new query strategy is devised in
the data labeling part, which combines the traditional uncertainty query strategy with the deep Bayesian uncertainty query
strategy. Finally, substantial tests are conducted to confirm the utility of the suggested approach on certain real-world data
sets. The results of the tests demonstrate that both the suggested method and query strategy are practical.
# Summary. An optional shortened abstract.
summary: This paper presents a novel deep semi-supervised clustering method with active learning, enhancing clustering performance by handling complex constraints and improving efficiency through active learning strategies.

tags:
  - Deep Learning

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://journals.indexcopernicus.com/api/file/viewByFileId/1843643'
url_code: 'https://journals.indexcopernicus.com/api/file/viewByFileId/1843643'
url_dataset: 'https://journals.indexcopernicus.com/api/file/viewByFileId/1843643'
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://journals.indexcopernicus.com/api/file/viewByFileId/184364'
url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Deep Constrained Clustering with Active Learning'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
