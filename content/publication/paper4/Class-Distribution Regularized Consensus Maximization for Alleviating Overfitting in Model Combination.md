---
title: 'Class-Distribution Regularized Consensus Maximization for Alleviating Overfitting in Model Combination'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors: 
 - admin
 - Jing Gao
 - Wei Fan
 - Deepak Turaga
 - Philip S Yu  

# Author notes (optional)
author_notes: 
  

date: '2014-08-24T00:00:00Z'
doi: 

# Schedule page publish date (NOT publication's date).
publishDate: '2014-08-24T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: International Conference on Knowledge Discovery and Data Mining
publication_short: ACM SIGKDD

abstract: In data mining applications such as crowdsourcing and privacy-preserving data mining, one may wish to obtain consolidated predictions out of multiple models without access to features of the data. Besides, multiple models usually carry complementary predictive information, model combination can potentially provide more robust and accurate predictions by correcting independent errors from individual models. Various methods have been proposed to combine predictions such that the final predictions are maximally agreed upon by multiple base models. Though this maximum consensus principle has been shown to be successful, simply maximizing consensus can lead to less discriminative predictions and overfit the inevitable noise due to imperfect base models. We argue that proper regularization for model combination approaches is needed to alleviate such overfitting effect. Specifically, we analyze the hypothesis spaces of several model combination methods and identify the trade-off between model consensus and generalization ability. We propose a novel model called Regularized Consensus Maximization (RCM), which is formulated as an optimization problem to combine the maximum consensus and large margin principles. We theoretically show that RCM has a smaller upper bound on generalization error compared to the version without regularization. Experiments show that the proposed algorithm outperforms a wide spectrum of state-of-the-art model combination methods on 11 tasks.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: 

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://dl.acm.org/doi/abs/10.1145/2623330.2623676'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'https://www.cs.uic.edu/~sxie/slides/kdd14_slides.pdf'
url_source: ''
url_video: 'https://customer-v0j10h1rfm4le10x.cloudflarestream.com/embed/sdk-iframe-integration.fla9.latest.js?video=eyJraWQiOiI3YjgzNTg3NDZlNWJmNDM0MjY5YzEwZTYwMDg0ZjViYiIsImFsZyI6IlJTMjU2In0.eyJzdWIiOiIzOWMwYTI4OWU3YmQyYzJhZGM4NDQ2NjU2NzM3OThiOCIsImV4cCI6MTczMDU4MTA1Niwia2lkIjoiN2I4MzU4NzQ2ZTViZjQzNDI2OWMxMGU2MDA4NGY1YmIifQ.0c5fVMqASS04o3AH2Q5jQRjGUjOe4T_cBly9w3afEEdmPdsZ9WKmqI0f8Engx11XvQHYY1isDyb-CAGvTzCQuyadLPsC8-8-57A1whk5cAf0RMSpsHGy-hNe717HZot3gZDRfvy3Prc5MUtGR1ZiBihzYYgGf5hBvJC97E-zixU_fBg6uxVhMTK7f6vbolYbxjGxr3UQH_FrUKx679Elav8N2j8FABVuHxLnHnFuKBSdYICK9FjLUSx2m0zC3fZDlR-VIUSfvj1sxV6xmPxRm4hrbzmACAqmm3ZGU8xGsTnvfW-KN-w7B-hLmRMRh3f4bMQcswqNtAVB3YirOb0cZQ'

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
