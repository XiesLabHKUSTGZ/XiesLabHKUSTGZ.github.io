---
title: 'Robust spammer detection by nash reinforcement learning'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: 
 - Yingtong Dou
 - Guixiang Ma
 - Philip S Yu
 - admin  

# Author notes (optional)
author_notes: 
  

date: '2020-08-23T00:00:00Z'
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: '2020-08-23T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: International Conference on Knowledge Discovery and Data Mining
publication_short: ACM SIGKDD

abstract: Online reviews provide product evaluations for customers to make decisions. Unfortunately, the evaluations can be manipulated using fake reviews ("spams") by professional spammers, who have learned increasingly insidious and powerful spamming strategies by adapting to the deployed detectors. Spamming strategies are hard to capture, as they can be varying quickly along time, different across spammers and target products, and more critically, remained unknown in most cases. Furthermore, most existing detectors focus on detection accuracy, which is not well-aligned with the goal of maintaining the trustworthiness of product evaluations. To address the challenges, we formulate a minimax game where the spammers and spam detectors compete with each other on their practical goals that are not solely based on detection accuracy. Nash equilibria of the game lead to stable detectors that are agnostic to any mixed detection strategies. However, the game has no closed-form solution and is not differentiable to admit the typical gradient-based algorithms. We turn the game into two dependent Markov Decision Processes (MDPs) to allow efficient stochastic optimization based on multi-armed bandit and policy gradient. We experiment on three large review datasets using various state-of-the-art spamming and detection strategies and show that the optimization algorithm can reliably find an equilibrial detector that can robustly and effectively prevent spammers with any mixed spamming strategies from attaining their practical goal. Our code is available at https://github.com/YingtongDou/Nash-Detect.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: ['Spam Detection', 'Reinforcement Learning', 'Adversarial Learning']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/3394486.3403135'
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
  caption: 
  focal_point: 
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
