---
title: "Adaptive Planning and Control with Time-Varying Tire Models for Autonomous Racing Using Extreme Learning Machine"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Qin Lin
- John M. Dolan
- -Under review, ICRA 2024


date: "2023-06-12T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Presented as late breaking paper, IROS 2023, Under review for ICRA 2024
# publication_short: In *ICRA 2022*

abstract: Autonomous racing is a challenging problem, as the vehicle needs to operate at the friction or handling limits in order to achieve minimum lap times. Autonomous race cars require highly accurate perception, state estimation, planning and precise application of controls. What makes it even more challenging is the accurate identification of vehicle model parameters that dictate the effects of the lateral tire slip, which may change over time, for example, due to wear and tear of the tires. Current works either propose model identification offline or need good parameters to start with (within 15-20% of actual vacdclue), which is not enough to account for major changes in tire model that occur during actual races when driving at the control limits. We propose a unified framework which learns the tire model online from the collected data, as well as adjusts the model based on environmental changes even if the model parameters change by a higher margin. We demonstrate our approach in numeric and high-fidelity simulators for a 1:43 scale race car and a full-size car. We also demonstrate results on a real RC car platform


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/abs/2303.08235'
url_code: 'https://github.com/dvij542/apacrace-code'
url_dataset: ''
url_poster: ''
url_project: 'https://dvij542.github.io/apacrace/'
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
