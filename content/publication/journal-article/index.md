---
title: "An example journal article"
authors:
- admin
- Robert Ford
author_notes:
- "Equal contribution"
- "Equal contribution"
date: "2023-12-06T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2023-12-06T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Optics and Laser Technology"
publication_short: "OLT"

abstract: Low-quality reconstruction is one main factor that greatly limits the development of snapshot compressive imaging (SCI) systems. The common algorithms usually unfold a 3D hyperspectral image (HSI) into a vector or matrix which inevitably corrupts the intrinsic structure of the HSI and insufficiently discovers its prior information. To fully exploit the underlying structures and internal correlations of the HSIs, this paper proposes a novel non-convex model based on Non-Local low-rank Tensor Approximation with Hyper-Laplacian priori (HL), named HL-NLTA, which effectively combines local and non-local similarity information from fused spectral and spatial perspectives. Specifically, a non-local low-rank tensor model based on the minimax concave plus (MCP) penalty and log sum (LS) penalty separately is developed which can simultaneously exploit two intrinsic properties of HSI, i.e., global correlation along the spectral domain (GCAS) and non-local self-similarity along the spatial domain (NSAS). Furthermore, the Hyper-Laplacian priori regularized through a non-convex ℓp (0 < p < 1) norm can preserve well the spectral and spatial structure. An optimization algorithm based on the alternating direction multiplier method (ADMM) framework is designed and accelerated by the Generalized shrinkage/ thresholding (GST) algorithm and the fast Fourier transform (FFT) to solve the new nonconvex model. Extensive simulation results on public datasets and experimental results on our real CASSI system indicate that the proposed method enables high-fidelity HSI reconstructions in terms of simultaneous spatial structure detail recovery and spectral preservation. These results verify the effectiveness of the proposed model for snapshot compressive imaging (e.g., Coded aperture snapshot spectral imaging CASSI).

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 
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
  caption: 'CASSI2.jpg'
  focal_point: ""
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
