---
title: 'HeteroSales: Utilizing heterogeneous social networks to identify the next enterprise customer'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: 
 - Qingbo Hu
 - admin
 - Jiawei Zhang
 - Qiang Zhu
 - Songtao Guo
 - Philip S Yu  

# Author notes (optional)
author_notes: 
  

date: '2016-04-11T00:00:00Z'
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: '2016-04-11T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: International World Wide Web Conference
publication_short: WWW

abstract: Nowadays, a modern e-commerce company may have both online sales and offline sales departments. Normally, online sales attempt to sell in small quantities to individual customers through broadcasting a large amount of emails or promotion codes, which heavily rely on the designed backend algorithms. Offline sales, on the other hand, try to sell in much larger quantities to enterprise customers through contacts initiated by sales representatives, which are more costly compared to online sales. Unlike many previous research works focusing on machine learning algorithms to support online sales, this paper introduces an approach that utilizes heterogenous social networks to improve the effectiveness of offline sales. More specifically, we propose a two-phase framework, HeteroSales, which first constructs a company-to-company graph, a.k.a. Company Homophily Graph (CHG), from semantics based meta-path learning, and then adopts label propagation on the graph to predict promising companies that we may successfully close an offline deal with. Based on the statistical analysis on the world's largest professional social network, LinkedIn, we demonstrate interesting discoveries showing that not all the social connections in a heterogeneous social network are useful in this task. In other words, some proper data preprocessing is essential to ensure the effectiveness of offline sales. Finally, through the experiments on LinkedIn social network data and third-party offline sales records, we demonstrate the power of HereroSales to identify potential enterprise customers in offline sales.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: 

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/2872427.2883000'
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
