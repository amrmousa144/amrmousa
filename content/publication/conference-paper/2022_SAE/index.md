---
title: 'Advanced Energy Management Strategies for Plug-In Hybrid Electric Vehicles via Deep Reinforcement Learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Gerhard Benedikt Weiss

# # Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2022-12-01T00:00:00Z'
doi: '10.4271/2022-01-7109'

# # Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: SAE 2022 Intelligent and Connected Vehicles Symposium
publication_short: ''

abstract: Plug-in Hybrid Electric Vehicles (PHEVs) achieve significant fuel economy by utilizing advanced energy management strategies in controlling the power distribution decision in real-time. Traditional heuristic approaches bring no additional benefits, including efficiency and development cost, considering the increasing complexity in control objectives. This paper extends a previous study of the same problem (RL) and vehicle topology to develop a Reinforcement Learning agent by investigating the performance of state-of-the-art algorithms, such as Rainbow-DQN with its variants, PPO and A3C, against the baseline rule-based and Dynamic Programming (DP) strategies. The developed RL agent is optimizing challenging control objectives such as fuel economy, vehicle drivability and driver comfort. The Rainbow-DQN is studied separately to optimize the agent compared to all the algorithm variants and after wards, the best performing variant is compared to tuned PPO and A3C agents. Proper evaluation criteria is defined and the concerned agents are tested with nine different scenarios to examine the generalization capabilities and performance robustness. The results revealed that the A3C agent surplussed both the PPO and the Rainbow-DQN achieving a maximum performance of 98.43% of the DP with a robustness of 97.32% ± 0.78 for the other cycles and an average of 177.7 sec for each engine start compared to 96.3 sec for the rule-based approach. Furthermore, as a future work, the paper investigated and proposed a cloud-based training concept for automated scaled-up training, evaluation and deployment of RL policies for the (P)HEVs of the future

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: 'https://saemobilus.sae.org/download/?fileFormat=pdf&cid=1000446636'
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
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
