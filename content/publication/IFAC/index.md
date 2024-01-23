---
title: "Towards Safety Assured End-to-End Vision-Based Control for Autonomous Racing"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Qin Lin
- John M. Dolan
- -IFAC World Congress 2023


date: "2021-07-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-03-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: IFAC World Congress 2023
# publication_short: In *ICRA 2022*

abstract: Autonomous car racing is a challenging task, as it requires precise applications of control while the vehicle is operating at cornering speeds. Traditional autonomous pipelines require accurate pre-mapping, localization, and planning which make the task computationally expensive and environment-dependent. Recent works propose use of imitation and reinforcement learning to train end-to-end deep neural networks and have shown promising results for high-speed racing. However, the end-to-end models may be dangerous to be deployed on real systems, as the neural networks are treated as black-box models devoid of any provable safety guarantees. In this work we propose a decoupled approach where an optimal end-to-end controller and a state prediction end-to-end model are learned together, and the predicted state of the vehicle is used to formulate a control barrier function for safeguarding the vehicle to stay within lane boundaries. We validate our algorithm both on a high-fidelity Carla driving simulator and a 1/10-scale RC car on a real track. The evaluation results suggest that using an explicit safety controller helps to learn the task safely with fewer iterations and makes it possible to safely navigate the vehicle on the track along the more challenging racing line.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2303.02267'
url_code: 'https://github.com/dvij542/End-to-end'
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
