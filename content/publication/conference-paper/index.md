---
title: 'A new algorithm for CASSI reconstruction'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  #- Robert Ford

# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2023-07-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-06T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-journal']

# Publication name and optional abbreviated publication name.
publication: Optics and Lasers in Engineering
publication_short: In *OLEN*

abstract: Snapshot compressive spectral imaging (SCI) is a potential technology in the field of hyperspectral imaging (HSI),where multi-frame spectral images are compressed into a single snapshot measurement and collected by a 2D detector. Existing reconstruction algorithms of SCI systems do not make full use of the redundancy of hyperspectral data, artifacts and blur degrade the quality of the reconstruction target image. In this paper, an efficient algorithm, named as spatial structural sparsity and spectral low-rank priors (SSS-SLR), is proposed based on two inherent priors of hyperspectral images. Specifically, the spatial structural sparsity and spectral low-rank priori
are simultaneously integrated into the SCI image restoration process to establish a variational optimization model, which can be solved via an alternating minimization algorithm. Extensive reconstruction results of hyperspectral data cube from both synthetic and real datasets demonstrate that the proposed method significantly outperforms
the canonical algorithms.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

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
  caption: 'featured.jpg'
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
