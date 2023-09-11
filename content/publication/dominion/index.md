---
title: "Learning Various Strategies For Dominion Using Deep Reinforcement Learning"
authors:
- admin
- Steve Engels
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2023-08-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-08-15T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: 19th AAAI Conference on Artificial Intelligence and Interactive Digital Entertainment
publication_short: AIIDE-23

abstract: Deck-building games, like Dominion, present an unsolved challenge for game AI research. The complexity arising from card interactions and the relative strength of strategies depending on the game configuration result in computer agents being limited to simple strategies. This paper describes the first application of recent advances in Geometric Deep Learning to deck-building games. We utilize a comprehensive multiset-based game representation and train the policy using a Soft Actor-Critic algorithm adapted to support variable-size sets of actions. The proposed model is the first successful learning-based agent that makes all decisions without relying on heuristics and supports a broader set of game configurations. It exceeds the performance of all previous learning-based approaches and is only outperformed by search-based approaches in certain game configurations. In addition, the paper presents modifications that induce agents to exhibit novel human-like play strategies. Finally, we show that learning strong strategies based on card combinations requires a reinforcement learning algorithm capable of discovering and executing a precise strategy while ignoring simpler suboptimal policies with higher immediate rewards.

# Summary. An optional shortened abstract.
summary: We use a graph-based game representation and a modified Soft Actor-Critic algorithm to train a deck-building game agent that outperforms all previous learning-based approaches and manipulate training so that the agents exhibit novel human-like play strategies.

tags: []
featured: false

# links:
# - name: ""
#   url: ""

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_abstract: '/publication/dominion/'
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Rio Grande Games**](https://www.riograndegames.com/games/dominion/)'
  focal_point: ""
  preview_only: true

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
slides: ""
---

