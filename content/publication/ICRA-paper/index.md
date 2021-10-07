---
title: "An Adaptable Approach to Learn Realistic Legged Locomotion without Examples"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
- dordonez
- Antonio Agudo
- Mario Martin
- Francesc Moreno-Noger

# Author notes (optional)
author_notes:
-
-
- "Equal supervision"
- "Equal supervision"

date: "2020-09-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Submitted to ICRA 2022 - pending aproval
publication_short: ICRA

abstract: Learning controllers that reproduce legged locomotion in nature has been a long-time goal in robotics and computer graphics. While yielding promising results, recent approaches are not yet flexible enough to be applicable to various legged systems. This is in part because they often rely on precise motion capture references or elaborate learning environments that ensure the naturality of the emergent locomotion gaits, but prevent generalization. This work proposes a generic approach for learning realistic legged locomotion for any legged system by guiding the learning process only with the low-order spring-loaded-inverted-pendulum model as a reference. Leveraging on the exploration capacities of reinforcement learning, we learn through experimentation a series of control policies that fill in the information gap between the template model and full-body dynamics required to maintain stable and periodic locomotion. With this learning framework, we show that even in a model-free setup and with a simple reactive control architecture, the learned policies can generate energy-efficient natural-looking locomotion gaits for a biped and a quadruped robot. And most importantly, this is achieved without using motion capture, strong constraints in the dynamics or kinematics of the robot, or prescribing limb coordination. A supplemental video is provided for qualitative analysis of the naturality of the learned gaits.

# Summary. An optional shortened abstract.
summary:

tags: [Robotics, Spring-Loaded inverted pendulum, Reinforcement Learning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
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

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}} -->
- Preprint pending for open-access

- Code soon to be released


{{< youtube qFSFVzTadtE >}}
<!--
Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->