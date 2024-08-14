---
title: "On discrete symmetries of robotic systems: A data-driven and group-theoretic analysis"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Daniel Ordonez-Apraez
- Antonio Agudo
- Mario Martin
- Francesc Moreno-Noguer

# Author notes (optional)
#author_notes:
#-
#-
#-
#-

date: "2023-01-28T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2302.10433"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Robotics Science and Systems (RSS) 2023
publication_short: RSS 2023

abstract: We present a comprehensive study on discrete morphological symmetries of dynamical systems, which are commonly observed in biological and artificial locomoting systems, such as legged, swimming, and flying animals/robots/virtual characters. These symmetries arise from the presence of one or more planes/axis of symmetry in the system's morphology, resulting in harmonious duplication and distribution of body parts. Significantly, we characterize how morphological symmetries extend to symmetries in the system's dynamics, optimal control policies, and in all proprioceptive and exteroceptive measurements related to the system's dynamics evolution. In the context of data-driven methods, symmetry represents an inductive bias that justifies the use of data augmentation or symmetric function approximators. To tackle this, we present a theoretical and practical framework for identifying the system's morphological symmetry group $\G$ and characterizing the symmetries in proprioceptive and exteroceptive data measurements. We then exploit these symmetries using data augmentation and $\G$-equivariant neural networks. Our experiments on both synthetic and real-world applications provide empirical evidence of the advantageous outcomes resulting from the exploitation of these symmetries, including improved sample efficiency, enhanced generalization, and reduction of trainable parameters.
# Summary. An optional shortened abstract.
summary: "Robotics Science and Systems (RSS - 2023)"

tags: [Robotics, Group Theory, Symmetries, Morphological Symmetries, Locomotion]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
links:
- icon:
  icon_pack: ai
  name: arXiv
  url: https://arxiv.org/abs/2302.10433
- icon:
  icon_pack: fab
  name: github
  url: https://github.com/Danfoa/MorphoSymm

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://github.com/Danfoa/MorphoSymm'
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/Tadba3dq1ns'

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
For intuition before theory, see the following presentation video. For theory read the paper. For fun and experimentation see the MorphoSymm repository.

{{< youtube qu4jIViRU1A >}}
