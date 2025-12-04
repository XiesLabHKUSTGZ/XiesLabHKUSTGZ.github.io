---
title: 'Dual attention network for product compatibility and function satisfiability analysis'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: 
 - Hu Xu
 - admin
 - Lei Shu
 - Philip S Yu  

# Author notes (optional)
author_notes: 
  

date: '2018-02-02T00:00:00Z'
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: '2018-02-02T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Association for the Advancement of Artificial Intelligence
publication_short: AAAI

abstract: Product compatibility and functionality are of utmost importance to customers when they purchase products, and to sellers and manufacturers when they sell products. Due to the huge number of products available online, it is infeasible to enumerate and test the compatibility and functionality of every product. In this paper, we address two closely related roblems product compatibility analysis and function satisfiability analysis, where the second problem is a generalization of the first problem (e.g., whether a product works with another product can be considered as a special function). We first identify a novel question and answering corpus that is up-to-date regarding product compatibility and functionality information. To allow automatic discovery product compatibility and functionality, we then propose a deep learning model called Dual Attention Network (DAN). Given a QA pair for a to-be-purchased product, DAN learns to 1) discover complementary products (or functions), and 2) accurately predict the actual compatibility (or satisfiability) of the discovered products (or functions). The challenges addressed by the model include the briefness of QAs, linguistic patterns indicating compatibility, and the appropriate fusion of questions and answers. We conduct experiments to quantitatively and qualitatively show that the identified products and functions have both high coverage and accuracy, compared with a wide spectrum of baselines.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: 

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://ojs.aaai.org/index.php/AAAI/article/view/12067'
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
