---
title: "An Adaptable Approach to Learn Realistic Legged Locomotion without Examples"

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
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: Preprint
publication_short: Preprint

abstract: In this work, we study discrete morphological symmetries of dynamical systems, a predominant feature in animal biology and robotic systems, expressed when the system's morphology has one or more planes of symmetry describing the duplication and balanced distribution of body parts. These morphological symmetries imply that the system's dynamics are symmetric (or approximately symmetric), which in turn imprints symmetries in optimal control policies and in all proprioceptive and exteroceptive measurements related to the evolution of the system's dynamics. For data-driven methods, symmetry represents an inductive bias that justifies data augmentation and the construction of symmetric function approximators. To this end, we use group theory to present a theoretical and practical framework allowing for (1) the identification of the system's morphological symmetry group $\G$, (2) data-augmentation of proprioceptive and exteroceptive measurements, and (3) the exploitation of data symmetries through the use of $\G$-equivariant/invariant neural networks, for which we present experimental results on synthetic and real-world applications, demonstrating how symmetry constraints lead to better sample efficiency and generalization while reducing the number of trainable parameters.

# Summary. An optional shortened abstract.
summary: Study of morphological symmetries of dynamical systems and their implications for learning algorithms.

tags: [Robotics, Group Theory, Symmetries, Morphological Symmetries]

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
  url: https://github.com/Danfoa/RobotEquivariantNN

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://github.com/Danfoa/RobotEquivariantNN'
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

### $\mathcal{G}=\mathcal{C}_2$: Reflection Symmetry
|                                                              Solo-C2   	                                                               |                                                                Atlas   	                                                                |                                                                Bolt   	                                                                |                                                                A1 	                                                                |   
|:--------------------------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------------------:|
| 	![solo-symmetries_anim_static](https://user-images.githubusercontent.com/8356912/203265566-ca07eb13-8b50-4ee1-ada7-6ebc985c4e30.gif)  | 	 ![atlas-symmetries_anim_static](https://user-images.githubusercontent.com/8356912/200183197-94242c57-bd9d-41cb-8a0b-509dceef5cb9.gif) |  ![bolt-symmetries_anim_static](https://user-images.githubusercontent.com/8356912/200183086-98d636d7-75b2-4744-b77f-99b3a1ec8e39.gif)  | ![a1-symmetries_anim_static](https://user-images.githubusercontent.com/8356912/203263932-1258a540-41d9-4b3d-9eb3-b67a840a7f5a.gif) | 	        
 |                                                             **Cassie**   	                                                             |                                                             **Baxter**   	                                                              |                                                               **HyQ**-C2  	                                                               |                                                                ---	                                                                |   
| ![cassie-symmetries_anim_static](https://user-images.githubusercontent.com/8356912/203263954-331759e7-72da-4530-b5f1-a51c328b8ad6.gif) | ![baxter-symmetries_anim_static](https://user-images.githubusercontent.com/8356912/203263946-7252bcd3-e4e5-48a4-842e-906b50df9122.gif)  | ![hyq-c2-symmetries_anim_static](https://user-images.githubusercontent.com/8356912/203263960-ee553b56-f781-40ac-8daa-d7e1c59f10e7.gif) |                                                               ------                                                               |

### $\mathcal{G}=\mathcal{K}_4$: Klein-Four Symmetry
|                                                     Solo   	                                                      |                                                                HyQ   	                                                                |   
|:-----------------------------------------------------------------------------------------------------------------:|:-------------------------------------------------------------------------------------------------------------------------------------:|
| 	![Solo-K4](https://user-images.githubusercontent.com/8356912/191269534-af143f29-1f46-4009-858b-72a63b5c67ac.gif) | 	 ![hyq-symmetries_anim_static](https://user-images.githubusercontent.com/8356912/203263962-3ee004db-f2f9-468c-ba89-04f3cd316c0d.gif) |        
