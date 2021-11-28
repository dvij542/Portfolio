---
title: "[RE] It Is Not the Journey but the Destination: Endpoint Conditioned Trajectory Prediction"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Yash Khandelwal
- admin
- Nikhil Popli
- Abhishek Shukla
- \*



date: ""2020-12-13T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-08-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Under review at 'Workshop on Adversarial Machine Learning and Beyond', AAAI 2021
# publication_short: In *ICRA 2022*

abstract: The paper reproduced in this report aims to tackle multiple pedestrian trajectory predictions using rich multi-modal predictions for the use of autonomous vehicles, social robots, etc. Earlier approaches to this problem have been auto-regressive in nature, i.e., using n points (or analogically, data from the last t seconds) from the dataset to produce the immediately next point, and then this process recurs.  In this paper, the end-point distribution conditioned on the past trajectory and the past trajectory features are modelled separately for each pedestrian. The future trajectory points are predicted based on the past and features from other pedestrians via social pooling. An assumption in this model is the absence of passive pedestrians or the fact that each pedestrian has an actual preconceived end-point or destination and is motivated to reach it. To formulate this report, we have experimented on the author's code by adding/removing social pooling layers, using truncation tricks, visualisation tools, and changing between CVAE and VAE architectures to verify all the claims made by the author described in detail below. We also performed some experiments such as shifting origin to the current point, using different architecture for encoder and decoder networks with the hope of improving the results, which are also described in detail at the end.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://openreview.net/pdf?id=5M4oJ5b6Dc_'
url_code: 'https://github.com/yash12khandelwal/PECNet-RC2020'
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

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
