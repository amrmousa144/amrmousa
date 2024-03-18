---
title: "AI-based Energy Management Strategies for P2 Plug-in Hybrid Electric Vehicles"
authors:
- admin
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2021-11-01T00:00:00Z"
doi: "10.5281/zenodo.7684683"

# # Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["thesis"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Plug-in Hybrid Electric Vehicles (PHEVs) offer a promising solution for the increasing CO2 emission problem. However, the improved economy of PHEVs strongly depends on the control strategy that decides on the power distribution between the Internal Combustion Engine (ICE) and the electric battery. Traditional rule-based control strategies are no more practical considering the increasing and more complex control objectives introduced by the emerging technologies such as automated driving and connected vehicles. In this study, an advanced Energy Management Strategy (EMS) based on Deterministic Dynamic Programming (DDP) and Reinforcement Learning (RL) is developed. DDP solves a finite-horizon optimization problem given the driving cycle a priori to obtain a global optimal vehicle power distribution that contributes mostly to the fuel economy improvements. DDP results are used to benchmark the subsequent RL-developed algorithms’ performance. In the newly proposed control strategy, an adaptive online learning RL agent is introduced into the existing Hybrid Control Unit (HCU) architecture solving the EMS for near-optimal solutions. The objective is to minimize the vehicle's expected total fuel consumption with a proper battery depletion rate besides penalizing the frequent engine on/off switching. Several RL-based algorithms have been experimented with using a vehicle model simulation. As a result, an Extended Deep Q-Network (E-DQN) agent is proposed by the thesis, trained on one cycle, and deployed on two other cycles to evaluate the performance. The thesis findings showed that E-DQN outperformed the rule-based strategy achieving up to 10.46% improvement in fuel economy closer to the DP performance alongside providing adequate compliance with the vehicle drivability and driver com-fort objectives.

tags:
  - Plug-in Hybrid Electric Vehicles
  - Energy Management Strategy
  - Deterministic Dynamic Programming
  - Reinforcement Learning
  - Machine learning
  - Deep Neural Networks
  - Model-based RL
featured: false

# links:
# - name: ""
#   url: ""
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
  focal_point: ""
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
slides: ''
---


