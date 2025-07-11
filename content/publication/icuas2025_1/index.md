---
title: 'RL-based Control of UAS Subject to Significant Disturbance'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - K. Chakraborty
  - T. Hof
  - A. Alharbat
  - A. Mersha

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-04-01T00:00:00Z'
# doi: '10.1109/ICUAS54217.2022.9836221'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
# publication: ICUAS2025_RL
# publication_short: ICUAS2025_RL

abstract: This paper proposes a Reinforcement Learning (RL)-based control framework for position and attitude control of an Unmanned Aerial System (UAS) subjected to significant disturbance that can be associated with an uncertain trigger signal. The proposed method learns the relationship between the trigger signal and disturbance force, enabling the system to anticipate and counteract the impending disturbances before they occur. We train and evaluate three policies a baseline policy trained without exposure to the disturbance, a reactive policy trained with the disturbance but without the trigger signal, and a predictive policy that incorporates the trigger signal as an observation and is exposed to the disturbance during training. Our simulation results show that the predictive policy outperforms the other policies by minimizing position deviations through a proactive correction maneuver. This work highlights the potential of integrating predictive cues into RL frameworks to improve UAS performance.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Aerial Robotics, Reinforcement Learning]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2504.08114'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://youtu.be/ETapj0mE1kk'

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
  - AeroSTREAM
#   - MARS4Earth

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
