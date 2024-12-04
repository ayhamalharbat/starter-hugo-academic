---
title: 'Three Fundamental Paradigms for Aerial Physical Interaction Using Nonlinear Model Predictive Control'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - A. Alharbat
  - H. Esmaeeli 
  - D. Bicego 
  - A. Y. Mersha
  - A. Franchi

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-06-01T00:00:00Z'
doi: '10.1109/ICUAS54217.2022.9836221'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
# publication: ICUAS2022
# publication_short: ICUAS2022

abstract: This paper introduces and compares the three most relevant approaches in which an Aerial Physical Interaction (APhI) control can include a Nonlinear Model Predictive Control (NMPC) paradigm in its design. All these methods have the advantage of being able to cope seamlessly with input and state constraints when compared to reactive controllers, however, they substantially differ in the design of the cost function. In the NMPC impedance control the cost function includes the error from the desired impedance dynamics; in the NMPC cascaded control the cost function includes the error from a reference trajectory which is generated online by an admittance filter driven by the force measurement; and in the NMPC hybrid position/force control the cost function contains both the trajectory and direct force error. The three architectures are proposed, implemented, analysed, validated, and compared with real-time simulations of interaction tasks with different environments. The numerical investigation provides a set of insights about the performances, advantages, and dependency on the design assumptions of the three methods.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Aerial Robotics, Aerial Physical Interaction, Model Predective Control]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

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
  - MARS4Earth

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
