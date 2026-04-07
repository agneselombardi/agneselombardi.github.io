---
title: ToM in LLM is not ToM, but a Pragmatic Effect

event: The 15th Workshop on Cognitive Modeling and Computational Linguistics (CMCL)
event_url: 'https://sites.google.com/view/cmclworkshop/home?authuser=0'

location: Palma, Mallorca (Spain)
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

abstract: |
    Instruction tuning has been shown to improve large language models’ performance on pragmatic tasks, and recent
    work suggests that additional training can also enhance Theory of Mind (ToM)–like abilities. However, existing
    studies rarely examine how different alignment techniques and training data contribute to ToM-related behavior in
    language models. In this work, we investigate the respective roles of instruction tuning and preference learning in
    shaping pragmatic and ToM abilities. Using the LLaMA 3 8B architecture, we fine-tune models on either pragmatic
    or ToM-specific data and subsequently align them via Direct Preference Optimization. We evaluate the resulting
    models on benchmarks targeting both pragmatics and ToM. Our results show that pragmatic training can substantially
    improve ToM performance even without explicit belief-related supervision, and that instruction tuning plays a central role in model alignment. These findings clarify the relationship between pragmatics and ToM in large language models.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2026-05-16'
# date_end: ''
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-09-13T00:00:00Z'

authors:
  - admin
  - Alessandro Lenci

tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: ''
  focal_point: Right

links:
#  - icon: twitter
#    icon_pack: fab
#    name: Follow
#    url: https://twitter.com/georgecushen
# url_code: 'https://github.com'
url_pdf: ''
# url_slides: 'https://slideshare.net'
# url_video: 'https://youtube.com'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
url_slides: 


# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
#   - example
---