---
title: 'Invariant Spatiotemporal Representation Learning for Cross-patient Seizure Classification'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Yuntian Yang
  - Jiabao Sean Xiao
  - Chuan Zhou
  - Haochen Sui
  - Haoxuan Li

# Author notes (optional)
author_notes:
  - "Equal contribution"
  - "Equal contribution"

date: '2024-10-12T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-10-15T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *The First Workshop on NeuroAI @ NeurIPS2024*
publication_short: In *NeuroAI @ NeurIPS2024*

abstract: Automatic seizure type classification from electroencephalogram (EEG) data can help clinicians to better diagnose epilepsy. Although many previous studies have focused on the classification problem of seizure EEG data, most of these methods require that there is no distribution shift between training data and test data, which greatly limits the applicability in real-world scenarios. In this paper, we propose an invariant spatiotemporal representation learning method for cross-patient seizure classification. Specifically, we first split the spatiotemporal EEG data into different environments based on heterogeneous risk minimization to reflect the spurious correlations. We then learn invariant spatiotemporal representations and train the seizure classification model based on the learned representations to achieve accurate seizure-type classification across various environments. The experiments are conducted on the largest public EEG dataset, the Temple University Hospital Seizure Corpus (TUSZ) dataset, and the experimental results demonstrate the effectiveness of our method.

# Summary. An optional shortened abstract.
summary: In this paper, we propose an invariant spatiotemporal representation learning method for cross-patient seizure classification. 

tags:
  - applications to neuroscience & cognitive science

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/forum?id=Ex6wAivo7G'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---
