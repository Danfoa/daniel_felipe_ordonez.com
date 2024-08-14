---
title: "Leveraging Symmetry in RL-based Legged Locomotion Control"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- Zhi Su
- Xiaoyu Huang
- Daniel Ordoñez-Apraez
- Yunfei Li
- Zhongyu Li
- Qiayuan Liao
- Giulio Turrisi
- Massimiliano Pontil
- Claudio Semini
- Yi Wu
- Koushil Sreenath


# Author notes (optional)
#author_notes:
#-
#-
#-
#-

date: "2024-06-28T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: International Conference on Intelligent Robots and Systems 2024
publication_short: IROS 2024

abstract: "Model-free reinforcement learning is a promising approach for autonomously solving challenging robotics control problems, but faces exploration difficulty without information of the robot's kinematics and dynamics morphology. The under-exploration of multiple modalities with symmetric states leads to behaviors that are often unnatural and sub-optimal. This issue becomes particularly pronounced in the context of robotic systems with morphological symmetries, such as legged robots for which the resulting asymmetric and aperiodic behaviors compromise performance, robustness, and transferability to real hardware. To mitigate this challenge, we can leverage symmetry to guide and improve the exploration in policy learning via equivariance/invariance constraints. In this paper, we investigate the efficacy of two approaches to incorporate symmetry: modifying the network architectures to be strictly equivariant/invariant, and leveraging data augmentation to approximate equivariant/invariant actor-critics. We implement the methods on challenging loco-manipulation and bipedal locomotion tasks and compare with an unconstrained baseline. We find that the strictly equivariant policy consistently outperforms other methods in sample efficiency and task performance in simulation. In addition, symmetry-incorporated approaches exhibit better gait quality, higher robustness and can be deployed zero-shot in real-world experiments."

# Summary. An optional shortened abstract.
summary: International Conference on Intelligent Robots and Systems 2024 (IROS - 2024)

tags: [Robotics, Morphological symmetries, Reinforcement Learning, Legged robot, quadruped robot,  Deep learning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org
links:
- icon:
  icon_pack: ai
  name: arxiv
  url: https://arxiv.org/abs/2403.17320

url_pdf: 'https://hybrid-robotics.berkeley.edu/publications/Symmetry_RL_LeggedLoco.pdf'
url_code: ''
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
