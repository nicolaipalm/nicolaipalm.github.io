---
title: "Parameter Individual Optimal Experimental Design and Calibration of Parametric Models"
authors:
- admin
- Florian Stroebl
- Herbert Palm
author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-10-21T00:00:00Z"
doi: "10.1109/ACCESS.2022.3216364"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["Journal Article"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Access"
publication_short: ""

abstract: Parametric models allow to reflect system behavior in general and characterize individual system instances by specific parameter values. For a variety of scientific disciplines, model calibration by parameter quantification is therefore of central importance. As the time and cost of calibration experiments increases, the question of how to determine parameter values of required quality with a minimum number of experiments comes to the fore. In this paper, a methodology is introduced allowing to quantify and optimize achievable parameter extraction quality based on an experimental plan including a process and methods how to adapt the experimental plan for improved estimation of individually selectable parameters. The resulting parameter-individual optimal design of experiments (pi-OED) enables experimenters to extract a maximum of parameter-specific information from a given number of experiments. We demonstrate how to minimize variance or covariances of individually selectable parameter estimators by model-based calculation of the experimental designs. Using the Fisher Information Matrix in combination with the Cramer-Raó inequality, the pi-OED plan is reduced to a global optimization problem. The pi-OED workflow is demonstrated using computer experiments to calibrate a model describing calendrical aging of lithium-ion battery cells. Applying bootstrapping methods allows to also quantify parameter estimation distributions for further benchmarking. Comparing pi-OED based computer experimental results with those based on state-of-the-art designs of experiments, reveals its efficiency improvement. All computer experimental results are gained in Python and may be reproduced using a provided Jupyter Notebook along with the source code. Both are available under https://github.com/nicolaipalm/oed.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Statistics (Application)
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9926067
url_code: 'https://github.com/nicolaipalm/oed'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://ieeexplore.ieee.org/abstract/document/9926067'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides: 
---

<!-- {{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
