---
title: 'Robust Conformal Prediction under Distribution Shift via Physics-Informed Structural Causal Model'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Rui Xu
  - Yue Sun
  - Chao Chen
  - Parv Venkitasubramaniam
  - admin

# Author notes (optional)
author_notes:
  - ''
  - ''
  - ''
  - ''
  - 'Corresponding author: sihongxie@hkust-gz.edu.cn'

date: '2024-03-22T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2403.15025'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-22T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: arxiv
publication_short: arxiv

abstract: Uncertainty is critical to reliable decision-making with machine learning. Conformal prediction (CP) handles uncertainty by predicting a set on a test input, hoping the set to cover the true label with at least 1−α confidence. This coverage can be guaranteed on test data even if the marginal distributions $P_X$ differ between calibration and test datasets. However, as it is common in practice, when the conditional distribution $P_{Y|X}$ is different on calibration and test data, the coverage is not guaranteed and it is essential to measure and minimize the coverage loss under distributional shift at \textit{all} possible confidence levels. To address these issues, we upper bound the coverage difference at all levels using the cumulative density functions of calibration and test conformal scores and Wasserstein distance. Inspired by the invariance of physics across data distributions, we propose a physics-informed structural causal model (PI-SCM) to reduce the upper bound. We validated that PI-SCM can improve coverage robustness along confidence level and test domain on a traffic speed prediction task and an epidemic spread task with multiple real-world datasets.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: [Causal, Distribution]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2403.15025'
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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
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
