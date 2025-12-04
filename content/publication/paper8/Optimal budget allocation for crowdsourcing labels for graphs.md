---
title: 'Optimal budget allocation for crowdsourcing labels for graphs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: 
 - Adithya Kulkarni
 - Mohna Chakraborty
 - admin
 - Qi Li  

# Author notes (optional)
author_notes: 
  

date: '2023-07-31T00:00:00Z'
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: '2023-07-31T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Uncertainty in Artificial Intelligence
publication_short: UAI

abstract: 'Crowdsourcing is an effective and efficient paradigm for obtaining labels for unlabeled corpus employing crowd workers. This work considers the budget allocation problem for a generalized setting on a graph of instances to be labeled where edges encode instance dependencies. Specifically, given a graph and a labeling budget, we propose an optimal policy to allocate the budget among the instances to maximize the overall labeling accuracy. We formulate the problem as a Bayesian Markov Decision Process (MDP), where we define our task as an optimization problem that maximizes the overall label accuracy under budget constraints. Then, we propose a novel stage-wise reward function that considers the effect of worker labels on the whole graph at each timestamp. This reward function is utilized to find an optimal policy for the optimization problem. Theoretically, we show that our proposed policies are consistent when the budget is infinite. We conduct extensive experiments on five real-world graph datasets and demonstrate the effectiveness of the proposed policies to achieve a higher label accuracy under budget constraints.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: 

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://proceedings.mlr.press/v216/kulkarni23a.html'
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
