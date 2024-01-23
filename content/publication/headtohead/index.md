---
title: "Towards Optimal Head-to-Head Autonomous Racing with Curriculum Reinforcement Learning"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Qin Lin
- John Dolan
- -Presented at MADGames workshop, IROS 2023 and under review, RLC 2024


date: "2023-07-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Presented at MADGames workshop, IROS 2023 and under review, RLC 2024
# publication_short: In *ICRA 2022*

abstract: Autonomous head-to-head racing presents a formidable challenge, demanding vehicles to operate at the limits of friction and handling in pursuit of minimal lap times, all while strategically seeking to overtake or maintain the lead against opponents. In this study, we begin by advancing the state-of-the-art head-to-head racing environment by incorporating realistic high-fidelity vehicle dynamics with a non-linear tire model. Some prior attempts have sought to directly learn a policy in the complex vehicle dynamics environment but have failed to learn an optimal policy. Our approach, however, centers on a curriculum learning-based framework, progressively transitioning from a simpler vehicle model to a more complex real environment for an approximated optimal policy. Additionally, we propose an innovative safe reinforcement learning algorithm grounded in control barrier functions, which ensures the agent's safety without compromising optimality. We evaluate our framework on both the proposed head-to-head racing environment and the Safety Gym benchmarks.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2308.13491'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: 'https://sites.google.com/view/aamas-submission'
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
