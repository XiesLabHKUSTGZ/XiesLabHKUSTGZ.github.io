---
title: 'Linear Uncertainty Quantification of Graphical Model Inference'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: 
 - Chenghua Guo
 - Han Yu
 - Jiaxin Liu
 - Chao Chen
 - Qi Li
 - admin
 - Xi Zhang  

# Author notes (optional)
author_notes: 
  

date: '2024-12-07T00:00:00Z'
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: '2024-12-07T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: Conference on Neural Information Processing Systems
publication_short: NeurIPS

abstract: 'Uncertainty Quantification (UQ) is vital for decision makers as it offers insights into the potential reliability of data and model, enabling more informed and risk-aware decision-making. Graphical models, known for their capability to represent data with complex dependencies, are widely utilized across various domains. Existing sampling-based UQ methods are unbiased but cannot guarantee convergence and is time-consuming on large-scale graphs. There are fast UQ methods for graphical models with closed-form solutions and convergence guarantee but with biased uncertainty underestimation. We propose LinUProp, a UQ method that utilizes a novel linear propagation of uncertainty to model uncertainty among related nodes additively instead of multiplicatively, to offer linear scalability, guaranteed convergence, and unbiased closed-form solutions. Theoretically, we decompose the expected prediction error of the graphical model and prove that the uncertainty computed by LinUProp is the generalized variance component of the decomposition. Experimentally, we demonstrated that LinUProp is consistent with the sampling-based method but with linear scalability and fast convergence. Moreover, LinUProp outperforms competitors in uncertainty-based active learning on four real-world graph datasets, achieving higher accuracy with a lower labeling budget.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: 

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://nips.cc/virtual/2024/poster/94771'
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
