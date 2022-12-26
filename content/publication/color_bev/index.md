---
title: "Estimation of Appearance and Occupancy Information in Bird’s Eye View from Surround Monocular Images"

authors:
- Sarthak Sharma
- Unnikrishnan R Nair
- admin
- Menon Midhun S
- Srikanth Vidapanakal

# author_notes:
# - "Equal contribution"
# - "Equal contribution"
# - "Equal contribution"

date: "2022-11-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2022-11-08T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Robotics and Automation, 2022, Autonomy 2.0 Workshop*
publication_short: In *ICRA, Autonomy 2.0 Workshop*

abstract: Autonomous driving requires efficient reasoning about the location and appearance of the different agents in the scene, which aids in downstream tasks such as object detection, object tracking, and path planning. The past few years have witnessed a surge in approaches that combine the different taskbased modules of the classic self-driving stack into an End-toEnd(E2E) trainable learning system. These approaches replace perception, prediction, and sensor fusion modules with a single contiguous module with shared latent space embedding, from which one extracts a human-interpretable representation of the scene. One of the most popular representations is the Birds-eye View (BEV), which expresses the location of different traffic participants in the ego vehicle frame from a top-down view. However, a BEV does not capture the chromatic appearance information of the participants. To overcome this limitation, we propose a novel representation that captures various traffic participants appearance and occupancy information from an array of monocular cameras covering 360 deg field of view (FOV). We use a learned image embedding of all camera images to generate a BEV of the scene at any instant that captures both appearance and occupancy of the scene, which can aid in downstream tasks such as object tracking and executing language-based commands. We test the efficacy of our approach on synthetic dataset generated from CARLA.

# Summary. An optional shortened abstract.
summary: Estimation of Appearance of a scene increases the accuracy of Bird's Eye View (BEV) representation of the scene.  

tags:
- Deep Learning
- Computer Vision

featured: false

url_pdf: 'https://arxiv.org/pdf/2211.04557.pdf'
#url_code: ''
#url_dataset: '#'
#url_poster: '#'
#url_project: 'https://montrealrobotics.ca/probod/'
#url_slides: 'https://drive.google.com/file/d/1uRzz5S5P14dGctD8AjipC7gBgQvQcDvm/view'
#url_source: 'https://sites.google.com/view/aiad2020/home'
# url_video: https://youtu.be/q6cKYW0kX4s


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---

{{% alert note %}}
Click the *Cite* button above to view the bibtex.
{{% /alert %}}

