---
title: "Deep Neural Network for Slip Detection on
Ice Surface"
authors:
- Kent Wu
- Suzy He
- Geoff Fernie 
- Atena Roshan Fek 
author_notes:
date: "2021-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Source Themes, 1*(1)"
publication_short: ""

abstract: Slip-induced falls are among the most common causes of major occupational injuries and economic loss in Canada. Identifying the risk factors associated with slip events is key to developing preventive solutions to reduce falls. One factor is the slip-resistance quality of footwear, which is fundamental to reducing the number of falls. Measuring footwear slip resistance with the recently developed Maximum Achievable Angle (MAA) test requires a trained researcher to identify slip events in a simulated winter environment. The human capacity for information processing is limited and human error is natural, especially in a cold environment. Therefore, to remove conflicts associated with human errors, in this paper a deep three-dimensional convolutional neural network is proposed to detect the slips in real-time. The model has been trained by a new dataset that includes data from 18 different participants with various clothing, footwear, walking directions, inclined angles, and surface types. The model was evaluated on three types of slips: Maxi-slip, midi-slip, and mini-slip. This classification is based on the slip perception and recovery of the participants. The model was evaluated based on both 5-fold and Leave-One-Subject-Out (LOSO) cross validation. The best accuracy of 97% was achieved when identifying the maxi-slips. The minimum accuracy of 77% was achieved when classifying the no-slip and mini-slip trials. The overall slip detection accuracy was 86% with sensitivity and specificity of 81% and 91%, respectively. The overall accuracy dropped by about 2% in LOSO cross validation. The proposed slip detection algorithm is not only beneficial for footwear manufactures to improve their footwear slip resistance quality, but it also has other potential applications, such as improving the slip resistance properties of flooring in healthcare facilities, commercial kitchens, and oil drilling platforms.
# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: http://arxiv.org/pdf/1512.04133v1
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
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/).
