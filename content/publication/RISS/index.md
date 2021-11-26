---
title: "Delay-aware Robust Control for Safe Autonomous Driving"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Qin Lin
- John M. Dolan
- in RISS Journal 2021, Submitted at *IEEE Conference on Robotics and Automation 2022*


date: "2021-07-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: in RISS Journal 2021, Submitted at *IEEE Conference on Robotics and Automation 2022*
# publication_short: In *ICRA 2022*

abstract: With the advancement of affordable self-driving vehicles using complicated nonlinear optimization but limited computation resources, computation time becomes a matter of concern. Other factors such as actuator dynamics and actuator command processing cost also unavoidably cause delays. In high-speed scenarios, these delays are critical to the safety of a vehicle. Recent works consider these delays individually, but none unifies them all in the context of autonomous driving. Moreover, recent works inappropriately consider computation time as a constant or a large upper bound, which makes the control either less responsive or over-conservative. To deal with all these delays, we present a unified framework by 1) modeling actuation dynamics, 2) using robust tube model predictive control, 3) using a novel adaptive Kalman filter without assuming a known process model and noise covariance, which makes the controller safe while minimizing conservativeness. On one hand, our approach can serve as a standalone controller; on the other hand, our approach provides a safety guard for a highlevel controller, which assumes no delay. This can be used for compensating the sim-to-real gap when deploying a black-box learning-enabled controller trained in a simplistic environment without considering delays for practical vehicle systems.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2109.07101.pdf'
url_code: ''
url_dataset: ''
url_poster: 'https://drive.google.com/file/d/1sQuEeLgVsQYwyb63ykS_pa_0KlYc6iZJ/view?usp=sharing'
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://drive.google.com/file/d/1y94AV2gVPYaQFXaR3BEcO0hLEK2fvpS_/view?usp=sharing'

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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
