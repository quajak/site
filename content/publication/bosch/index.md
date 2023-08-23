---
title: 'An Enhanced Graph Representation for Machine Learning Based Automatic Intersection Management'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Marvin Klimke
  - admin
  - Benjamin Völz
  - Michael Buchholz

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-07-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In 2022 IEEE 25th International Conference on Intelligent Transportation Systems
publication_short: In ITSC

abstract: The improvement of traffic efficiency at urban intersections receives strong research interest in the field of automated intersection management. So far, mostly non-learning algorithms like reservation or optimization-based ones were proposed to solve the underlying multi-agent planning problem. At the same time, automated driving functions for a single ego vehicle are increasingly implemented using machine learning methods. In this work, we build upon a previously presented graph-based scene representation and graph neural network to approach the problem using reinforcement learning. The scene representation is improved in key aspects by using edge features in addition to the existing node features for the vehicles. This leads to an increased representation quality that is leveraged by an updated network architecture. The paper provides an in-depth evaluation of the proposed method against baselines that are commonly used in automatic intersection management. Compared to a traditional signalized intersection and an enhanced first-in-first-out scheme, a significant reduction of traversal duration is observed at varying traffic densities. Finally, the generalization capability of the graph-based representation is evaluated by testing the policy on intersection layouts not seen during training. The model generalizes virtually without restrictions to smaller intersection layouts and within certain limits to larger ones.

# Summary. An optional shortened abstract.
summary: We expand on the previously developed graph-based scene representation and graph neural network to approach the automated intersection management problem using reinforcement learning and show that the model outperforms baselines and generalizes very well.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2207.08655.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_abstract: '/publication/bosch/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Graph-based scene representation'
  focal_point: ''
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
