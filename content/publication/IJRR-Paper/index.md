---
title: "Morphological symmetries in robotics"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Daniel Ordoñez-Apraez 
- Giulio Turrisi 
- Vladimir Kostic
- Mario Martin  
- Antonio Agudo
- Francesc Moreno-Noguer
- Massimiliano Pontil
- Claudio Semini 
- Carlos Mastalli 
# Author notes (optional)
#author_notes:
#-
#-
#-
#-

date: "2024-09-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: IJRR 2024
publication_short: IJRR 2024

abstract: We present a comprehensive framework for studying and leveraging morphological symmetries in robotic systems. These are intrinsic properties of the robot's morphology, frequently observed in animal biology and robotics, which stem from the replication of kinematic structures and the symmetrical distribution of mass. We illustrate how these symmetries extend to the robot’s state space and both proprioceptive and exteroceptive sensor measurements, resulting in the equivariance of the robot’s equations of motion and optimal control policies. Thus, we recognize morphological symmetries as a relevant and previously unexplored physics-informed geometric prior, with significant implications for both data-driven and analytical methods used in modeling, control, estimation and design in robotics. For data-driven methods, we demonstrate that morphological symmetries can enhance the sample efficiency and generalization of machine learning models through data augmentation, or by applying equivariant/invariant constraints on the model's architecture. In the context of analytical methods, we employ abstract harmonic analysis to decompose the robot's dynamics into a superposition of lower-dimensional, independent dynamics. We substantiate our claims with both synthetic and real-world experiments conducted on bipedal and quadrupedal robots. Lastly, we introduce the repository [MorphoSymm](https://github.com/Danfoa/MorphoSymm?utm_source=\source) to facilitate the practical use of the theory and applications outlined in this work.

# Summary. An optional shortened abstract.
summary: International Journal of Robotics Research (Conditional accept IJRR-2024)

tags: [Robotics, Morphological symmetries, Equivariant deep learning, Harmonic analysis, Koopman operator, Quadrupedal robots, Bipedal robots]

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
  url: https://arxiv.org/abs/2402.15552

url_pdf: ''
url_code: 'https://github.com/Danfoa/MorphoSymm'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
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

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->

