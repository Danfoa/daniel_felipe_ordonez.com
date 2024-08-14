---
title: "Dynamics Harmonic Analysis of Robotic Systems: Application in Data-Driven Koopman Modeling"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Daniel Ordoñez-Apraez
- Vladimir Kostic
- Giulio Turrisi
- Pietro Novelli
- Carlos Mastalli
- Claudio Semini
- Massimiliano Pontil

# Author notes (optional)
#author_notes:
#-
#-
#-
#-

date: "2024-07-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Learning for dynamics and control 2024
publication_short: L4DC 2024

abstract: We introduce the use of harmonic analysis to decompose the state space of symmetric robotic systems into orthogonal isotypic subspaces. These are lower-dimensional spaces that capture distinct, symmetric, and synergistic motions. For linear dynamics, we characterize how this decomposition leads to a subdivision of the dynamics into independent linear systems on each subspace, a property we term dynamics harmonic analysis (DHA). To exploit this property, we use Koopman operator theory to propose an equivariant deep-learning architecture that leverages the properties of DHA to learn a global linear model of the system dynamics. Our architecture, validated on synthetic systems and the dynamics of locomotion of a quadrupedal robot, exhibits enhanced generalization, sample efficiency, and interpretability, with fewer trainable parameters and computational costs.

# Summary. An optional shortened abstract.
summary: Learning for dynamics and control 2024 (L4DC - 2024)

tags: [Robotics, Harmonic Analysis, Morphological symmetries, Koopman operator, Deep learning]

# Display this page in the Featured widget?
featured: True

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
links:
- icon:
  icon_pack: ai
  name: PMLR
  url: https://proceedings.mlr.press/v242/ordonez-apraez24a.html

url_pdf: 'https://danfoa.github.io/DynamicsHarmonicsAnalysis/static/pdfs/Dynamics%20Harmonic%20Analysis%20of%20Robotic%20Systems_Application%20in%20Data-Driven%20Koopman%20Modeling_Ordonez-2024-L4DC.pdf'
url_code: 'https://github.com/Danfoa/DynamicsHarmonicsAnalysis'
url_dataset: ''
url_poster: 'https://danfoa.github.io/DynamicsHarmonicsAnalysis/'
url_project: 'https://danfoa.github.io/DynamicsHarmonicsAnalysis/'
url_slides: 'https://docs.google.com/presentation/d/1si4F2eTbfOj1OPNnYDp50i-_iyN-MsOe8ZftTR5-gdM/pub?start=false&loop=false&delayms=10000'
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.#
#image:
#  caption:
#  focal_point: "Center"
#  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
#projects:
#- invite-ros-robotics

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
