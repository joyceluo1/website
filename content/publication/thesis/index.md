---
title: 'Equitable Data-Driven Facility Location and Resource Allocation to Fight the Opioid Epidemic'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Bartolomeo Stellato

# Author notes (optional)
# author_notes:
# - 'Equal contribution'
# - 'Equal contribution'

date: '2023-11-08'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: arXiv:2301.06179
publication_short: 

abstract: The opioid epidemic is a crisis that has plagued the United States (US) for decades. One central issue of the epidemic is inequitable access to treatment for opioid use disorder (OUD), which puts certain populations at a higher risk of opioid overdose. We integrate a predictive dynamical model and a prescriptive optimization problem to compute high-quality opioid treatment facility and treatment budget allocations for each US state. Our predictive model is a differential equation-based epidemiological model that captures the dynamics of the opioid epidemic. We use a process inspired by neural ordinary differential equations to fit this model to opioid epidemic data for each state and obtain estimates for unknown parameters in the model. We then incorporate this epidemiological model into a corresponding mixed-integer optimization problem (MIP) that aims to minimize the number of opioid overdose deaths and the number of people with OUD. We develop strong relaxations based on McCormick envelopes to efficiently compute approximate solutions to our MIPs that have a mean optimality gap of 3.99%. Our method provides socioeconomically equitable solutions, as it incentivizes investments in areas with higher social vulnerability (from the US Centers for Disease Control's Social Vulnerability Index) and opioid prescribing rates. On average, when allowing for overbudget solutions, our approach decreases the number of people with OUD by 9.03 ± 1.772%, increases the number of people in treatment by 88.75 ± 26.223%, and decreases the number of opioid-related deaths by 0.58 ± 0.111% after 2 years compared to the baseline epidemiological model's predictions. Our solutions show that policy-makers should target adding treatment facilities to counties that have significantly less facilities than their population share and are more socially vulnerable. Furthermore, we demonstrate that our optimization approach, guided by epidemiological and socioeconomic factors, should help inform these strategic decisions, as it yields population health benefits in comparison to benchmarks based solely on population and social vulnerability.

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: https://arxiv.org/pdf/2301.06179.pdf
url_code: https://github.com/joyceluo1/mip_opioid
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
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
