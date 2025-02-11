---
title: "Predicting Long-Term Opioid Use via Interpretable Machine Learning"
authors:
- admin
- Fernanda Bravo
- Elisa Long
date: "2025-03-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2018-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: "Under revision"

abstract: Sustained opioid use increases the risk of drug overdose and death, yet identifying patients at risk for long-term use is challenging. Prescription drug monitoring programs (PDMPs) collect data on all controlled substances dispensed, providing an opportunity to predict patients at risk and allow for early intervention by healthcare providers. While machine learning (ML) offers great potential for making these predictions, many models (e.g., neural networks) function as  ``black boxes'', making them difficult for practitioners to interpret and apply. The degree of interpretability typically depends on the number of input variables and whether users understand how those variables influence predictions. In this study, we develop a novel, interpretable risk-scoring rule to predict whether a patient with an opioid prescription eventually becomes a long-term user. Our scoring rule uses an optimization based algorithm riskSLIM (Ustun and Rudin, 2019) that fits a logistic regression with interpretability constraints (e.g., coefficients have to be small integers), which results in a large-scale mixed-integer nonlinear program, and is solved through a specialized cutting-plane algorithm. We analyze deidentified prescription data from California's PDMP, encompassing over 13 million opioid prescriptions dispensed to more than seven million opioid-naive individuals from 2018 to 2019. Our resulting scoring table uses only six variables and can identify over half of long-term opioid users within a month of their initial prescription, with predicted risks closely aligning with observed outcomes. It performs comparably to state-of-the-art machine learning models (e.g., XGBoost) while being much simpler and more customizable. Practitioners could quickly predict risk using basic arithmetic, evaluate the impact of changing input variables on outcomes, and adjust the table to accommodate specific needs and expert judgment. Our work demonstrates how optimization can be used to find interpretable models that perform as well as other high-performing ML models but are easier to understand and apply, opening opportunities for cross-disciplinary research between operations research and computer science.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Healthcare Operations
- Machine Learning

featured: true

# links:
# - name: Custom Link
#   url: http://example.org
# url_pdf: https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4008669
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
