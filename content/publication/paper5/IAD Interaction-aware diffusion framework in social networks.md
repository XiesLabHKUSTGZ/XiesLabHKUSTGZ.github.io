---
title: 'IAD: Interaction-aware diffusion framework in social networks'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: 
 - Xi Zhang
 - Yuan Su
 - Siyu Qu
 - admin
 - Binxing Fang
 - Philip S Yu

# Author notes (optional)
author_notes: 
  

date: '2018-07-19T00:00:00Z'
doi: '10.1109/TKDE.2018.2857492'

# Schedule page publish date (NOT publication's date).
publishDate: '2018-07-19T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: IEEE Transactions on Knowledge and Data Engineering
publication_short: IEEE TKDE

abstract: In networks, multiple contagions, such as information and purchasing behaviors, may interact with each other as they spread simultaneously. However, most of the existing information diffusion models are built on the assumption that each individual contagion spreads independently, regardless of their interactions. Gaining insights into such interaction is crucial to understand the contagion adoption behaviors, and thus can make better predictions. In this paper, we study the contagion adoption behavior under a set of interactions, specifically, the interactions among users, contagions' contents, and sentiments, which are learned from social network structures and texts. We develop an effective and efficient interaction-aware diffusion (IAD) framework, incorporating these interactions into a unified model. We also present a generative process to distinguish user roles, a co-training method to determine contagions' categories and a new topic model to obtain topic-specific sentiments. Evaluation on the large-scale Weibo dataset demonstrates that our proposal can learn how different users, contagion categories, and sentiments interact with each other efficiently. With these interactions, we can make a more accurate prediction than the state-of-art baselines. Moreover, we can better understand how the interactions influence the propagation process and thus can suggest useful directions for information promotion or suppression in viral marketing.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: 

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ieeexplore.ieee.org/abstract/document/8413173/'
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
