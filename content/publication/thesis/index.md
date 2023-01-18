---
title: 'Equitable Data-Driven Resource Allocation to Fight the Opioid Epidemic: A Mixed-Integer Optimization Approach'

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

date: '2023-01-18'
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

abstract: The opioid epidemic is a crisis that has plagued the United States (US) for decades. One central issue of the epidemic is inequitable access to treatment for opioid use disorder (OUD), which puts certain populations at a higher risk of opioid overdose. We integrate a predictive dynamical model and a prescriptive optimization problem to compute the optimal locations of opioid treatment facilities and the optimal treatment budget distribution in each US state. Our predictive model is a differential equationbased epidemiological model that captures the dynamics of the opioid epidemic. We use neural ordinary differential equations to fit this model to opioid epidemic data for each state and obtain estimates for unknown parameters in the model. We then incorporate this epidemiological model for each state into a corresponding mixed-integer optimization problem (MIP) for treatment facility location and resource allocation. Our MIPs aim to minimize the number of opioid overdose deaths and the number of people with OUD, and to target socioeconomic equitability by considering social vulnerability (from the US Centers for Disease Control's Social Vulnerability Index) and opioid prescribing rates in each county. Overall, our MIPs' proposed solutions on average decrease the number of people with OUD by 5.70±0.738%, increase the number of people in treatment by 21.17±3.162%, and decrease the number of opioid-related deaths by 0.51±0.086% after 2 years compared to the baseline epidemiological model's predictions. Rather than only evaluating the effectiveness of potential policies as in past literature, our approach is decision-focused and directly yields actionable insights for policy-makers. It provides concrete opioid treatment facility and budget allocations and quantifies the impact of these allocations on pertinent population health measures. Future iterations of this approach could be implemented as a decision-making tool to tackle the issue of opioid treatment inaccessibility.

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
