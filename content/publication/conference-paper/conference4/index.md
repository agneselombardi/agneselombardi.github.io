---
title: "ToM in LLM is not ToM, but a Pragmatic Effect"
authors:
- admin
- Alessandro Lenci
date: 2026-01-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: ""

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the 15th Workshop on Cognitive Modeling and Computational Linguistics"
publication_short: ""

abstract: Instruction tuning has been shown to improve large language models’ performance on pragmatic tasks, and recent work suggests that additional training can also enhance Theory of Mind (ToM)–like abilities. However, existing studies rarely examine how different alignment techniques and training data contribute to ToM-related behavior in language models. In this work, we investigate the respective roles of instruction tuning and preference learning in shaping pragmatic and ToM abilities. Using the LLaMA 3 8B architecture, we fine-tune models on either pragmatic or ToM-specific data and subsequently align them via Direct Preference Optimization. We evaluate the resulting models on benchmarks targeting both pragmatics and ToM. Our results show that pragmatic training can substantially improve ToM performance even without explicit belief-related supervision, and that instruction tuning plays a central rolei nmodel alignment. These findings clarify the relationship between pragmatics and ToM in large language models.

# Summary. An optional shortened abstract.
summary: ""

tags:
- ToM
- pragmatics
- LLMs
- interpretability

featured: true

links:

url_pdf: 'http://www.lrec-conf.org/proceedings/lrec2026/workshops/cmcl/pdf/2026.cmcl-1.4.pdf'
url_code: ''
url_dataset: ''
url_poster: 'https://unipiit-my.sharepoint.com/:b:/g/personal/a_lombardi19_studenti_unipi_it/IQDj_QF5QXDRQZNbV-8GGGLrAQy48kN89Kejdm7arXBcjTc?e=ZSPV2T'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ''
---

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
