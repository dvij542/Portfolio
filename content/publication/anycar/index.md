---
title: "Agile Mobility with Rapid Online Adaptation via Meta-learning and Uncertainty-aware MPPI"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Haoru Xue
- Wenli Xiao
- Tony Tao
- Guanya Shi
- John Dolan
- -Under review, ICRA 2025


date: "2024-06-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-07-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
# publication_short: In *ICRA 2022*

abstract: Modern non-linear model-based controllers require an accurate physics model and model parameters to be able to control mobile robots at their limits. Also, due to surface slipping at high speeds, the friction parameters may continually change (like tire degradation in autonomous racing), and the controller may need to adapt rapidly. Many works derive a task-specific robot model with a parameter adaptation scheme that works well for the task but requires a lot of effort and tuning for each platform and task. In this work, we design a full model-learning-based controller based on meta pre-training that can very quickly adapt using few-shot dynamics data to any wheel-based robot with any model parameters, while also reasoning about model uncertainty. We demonstrate our results in small-scale numeric simulation, the large-scale Unity simulator, and on a medium-scale hardware platform with a wide range of settings. We show that our results are comparable to domain-specific well-engineered controllers, and have excellent generalization performance across all scenarios.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2410.06565'
url_code: 'https://github.com/DRIVE-LAB-CMU/meta-learning-model-adaptation'
url_dataset: ''
url_poster: ''
url_project: 'https://sites.google.com/view/meta-learning-model-adaptation/home'
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=jjTQkG-LwdM'

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
