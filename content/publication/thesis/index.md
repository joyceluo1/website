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

date: '2022-04-05'
doi: ''

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['7']

# Publication name and optional abbreviated publication name.
publication: 
publication_short: 

abstract: 'The opioid epidemic is a crisis that has plagued the United States (US) for decades. One of the central issues of the epidemic is inequitable access to treatment for opioid use disorder (OUD), which puts certain populations at a higher risk of opioid overdose. This issue has not yet been systematically addressed using computational methods. In this work, we use real-world data and optimization to formulate the problem of finding the optimal locations of opioid treatment facilities and the optimal treatment budget distribution in each US state. To capture the dynamics of the changing opioid epidemic, we develop a state-level differential equation-based epidemiological model. We fit this model to current opioid epidemic data using neural ordinary differential equations, a useful framework that allows us to embed differential equations into a neural network layer. We then integrate this epidemiological model for each state into a corresponding mixed-integer optimization problem (MIP) for treatment facility location and resource allocation. We seek to minimize opioid overdose deaths and the number of people with OUD. Our MIPs also target socioeconomic equitability by considering social vulnerability (from the CDC's Social Vulnerability Index) and opioid prescribing rates in each county. This work lays the mathematical and computational foundations to assist governments, policymakers, and health professionals in combating the opioid epidemic.'

# Summary. An optional shortened abstract.
summary: ''

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: https://github.com/joyceluo1/senior-thesis
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
