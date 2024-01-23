---
title: "Delay-aware Robust Control for Safe Autonomous Driving and Racing"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Qin Lin
- John M. Dolan
- -*Transactions on Intelligent Transportation Systems (T-ITS)*


date: "2023-09-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: in RISS Journal 2021, Submitted at *IEEE Conference on Robotics and Automation 2022*
# publication_short: In *ICRA 2022*

abstract: Delays endanger safety of autonomous systems operating in a rapidly changing environment, such as nondeterministic surrounding traffic participants in autonomous driving and high-speed racing. Unfortunately, delays are typically not considered during the conventional controller design or learning-enabled controller training phases prior to deployment in the physical world. In this paper, the computation delay from nonlinear optimization for motion planning and control, as well as other unavoidable delays caused by actuators, are addressed systematically and unifiedly. To deal with all these delays, in our framework- 1) we propose a new filtering approach with no prior knowledge of dynamics and disturbance distribution to adaptively and safely estimate the time-variant computation delay; 2) we model actuation dynamics for steering delay; 3) all the constrained optimization is realized in a robust tube model predictive controller. For the application merits, we demonstrate that our approach is suitable for both autonomous driving and autonomous racing. Our approach is a novel design for a standalone delay compensation controller. In addition, in the case that a learning-enabled controller assuming no delay works as a primary controller, our approach serves as the primary controller's safety guard.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/document/10368187'
url_code: 'https://github.com/dvij542/Delay-aware-Robust-Tube-MPC'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://www.youtube.com/watch?v=bWNpzMi3RlI'

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
