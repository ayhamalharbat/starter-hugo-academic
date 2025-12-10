---
title: 'RA-L 2025 - Predictive Admittance Control for Aerial Physical Interaction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - A. Alharbat
  - C. Gabellieri
  - A. Mersha
  - A. Franchi

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-08-29T00:00:00Z'
# doi: '10.1109/ICUAS54217.2022.9836221'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
# publication: ICUAS2025_RL
# publication_short: ICUAS2025_RL

abstract: This paper introduces a novel approach for controlling aerial robots during physical interaction by integrating Admittance Control with Nonlinear Model Predictive Control (NMPC). Unlike existing methods, our technique incorporates the desired impedance dynamics directly into the NMPC prediction model, alongside the robot's dynamics. This allows for the explicit prediction of how the robot's impedance will respond to interaction forces within the prediction horizon. Consequently, our controller effectively tracks the desired impedance behavior during physical interaction while seamlessly transitioning to trajectory tracking in free motion, all while consistently respecting actuator constraints. The efficacy of this method is validated through real-time simulations and experiments involving physical interaction tasks with an aerial robot. Our findings demonstrate that, across most scenarios, our method significantly outperforms the state-of-the-art (which does not predict future impedance state), achieving a reduction in tracking error of up to 90\%. Furthermore, the results indicate that our approach enables smoother and safer physical interaction, characterized by reduced oscillations and the absence of the unstable behavior observed with the state-of-the-art method in certain situations.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Aerial Robotics, Aerial Physical Interaction, Model Predective Control]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
links:
- name: Early Access
  url: https://ieeexplore.ieee.org/document/11155162

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/oJJVfXT0mME'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - MAESTRO

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
