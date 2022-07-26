---
title: 'Equitable Data-Driven Resource Allocation to Fight the Opioid Epidemic: A Mixed-Integer Optimization Approach'

event: Top ORFE Theses Department Showcase
event_url: ''

location: Princeton University
address:
  street: ''
  city: Princeton
  region: NJ
  postcode: '08544'
  country: United States


summary: ''
abstract: 'The opioid epidemic is a crisis that has plagued the United States (US) for decades. One of the central issues of the epidemic is inequitable access to treatment for opioid use disorder (OUD), which puts certain populations at a higher risk of opioid overdose. This issue has not yet been systematically addressed using computational methods. In this work, we use real-world data and optimization to formulate the problem of finding the optimal locations of opioid treatment facilities and the optimal treatment budget distribution in each US state. To capture the dynamics of the changing opioid epidemic, we develop a state-level differential equation-based epidemiological model. We fit this model to current opioid epidemic data using neural ordinary differential equations, a useful framework that allows us to embed differential equations into a neural network layer. We then integrate this epidemiological model for each state into a corresponding mixed-integer optimization problem (MIP) for treatment facility location and resource allocation. We seek to minimize opioid overdose deaths and the number of people with OUD. Our MIPs also target socioeconomic equitability by considering social vulnerability (from the CDC’s Social Vulnerability Index) and opioid prescribing rates in each county. Our MIPs' proposed solutions on average decrease the number of people with OUD by 5.76%, increase the number of people in treatment by 21.60%, and decrease the number of opioid-related deaths by 0.52% after 2 years. This work lays the mathematical and computational foundations to assist governments, policymakers, and health professionals in combating the opioid epidemic.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2022-05-04'
# date_end: '2030-06-01T15:00:00Z'
all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: '2017-01-01T00:00:00Z'

authors: Joyce Luo
tags: []

# Is this a featured talk? (true/false)
featured: false

url_code: ''
url_pdf: ''
url_slides: ''
url_video: https://www.youtube.com/watch?v=vg9peCx3l5E&t=1258s

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
