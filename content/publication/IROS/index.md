---
title: "Online Adaptive Compensation for Model Uncertainty Using Extreme Learning Machine-based Control Barrier Functions"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Qin Lin
- John Dolan
- -IROS 2022


date: "2021-07-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: IROS 2022
# publication_short: In *ICRA 2022*

abstract: A control barrier functions-based quadratic programming (CBF-QP) method has emerged as a controller synthesis tool to assure safety of autonomous systems owing to the appealing safe forward invariant set. However, the provable safety relies on a precisely described dynamic model, which is not always available in practice. Recent works leverage learning to compensate model uncertainty for a CBF controller. However, these approaches based on reinforcement learning or episodic learning are limited to dealing with time-invariant uncertainty. Also, the reinforcement learning approach learns the uncertainty offline, while episodic learning only updates the controller after a batch of data is available by the end of an episode. Instead, we propose a novel tuning extreme learning machine (tELM)-based CBF controller that can compensate time-variant and time-invariant model uncertainty adaptively in an online manner. We validate our approach's effectiveness in a simulation of an Adaptive Cruise Control (ACC) system.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/9981680'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---
