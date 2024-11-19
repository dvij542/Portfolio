---
title: "Disturbance Observer-based Control Barrier Functions with Residual Model Learning for Safe Reinforcement Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Qin Lin
- John M Dolan
- -Under review, ICRA 2025


date: "2023-06-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
# publication_short: In *ICRA 2022*

abstract: Reinforcement learning (RL) agents need to explore their environment to learn optimal behaviors and achieve maximum rewards. However, exploration can be risky when training RL directly on real systems, while simulation-based training introduces the tricky issue of the sim-to-real gap. Recent approaches have leveraged safety filters, such as control barrier functions (CBFs), to penalize unsafe actions during RL training. However, the strong safety guarantees of CBFs rely on a precise dynamic model. In practice, uncertainties always exist, including internal disturbances from the errors of dynamics and external disturbances such as wind. In this work, we propose a new safe RL framework based on disturbance rejection-guarded learning, which allows for an almost model-free RL with an assumed but not necessarily precise nominal dynamic model. We demonstrate our results on the Safety-gym benchmark for Point and Car robots on all tasks where we can outperform state-of-the-art approaches that use only residual model learning or a disturbance observer (DOB). We further validate the efficacy of our framework using a physical F1/10 racing car.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2410.06570'
url_code: 'https://github.com/dvij542/RES-DOB-CBF'
url_dataset: ''
url_poster: ''
url_project: 'https://sites.google.com/view/res-dob-cbf-rl/home'
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=iP1EZfdM9tM'

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
