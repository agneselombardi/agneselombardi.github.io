---
title: Do Large Language Models Predict When the Brain Expects a Metaphor? LLM Surprisal Reveals Theory-of-Mind Dependent Neural Alignment?

event: Psycholinguistics in Flanders (PiF)
event_url: 'https://sites.google.com/view/pifpavia'

location: Pavia
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

abstract: |
  Understanding metaphors involve more than detecting an unexpected word. Metaphors require inferring communicative intentions that go beyond literal meanings, and often map abstract concepts onto more concrete domains of experience, hence engaging Theory of Mind (ToM). Recently, Canal et al. (2022) records the EEG response to physical and mental metaphors (i.e., metaphors referring to behavioral and psychological features, respectively) and assessed participants’ ToM using the Reading the Mind in the Eyes Test (RMET). They show that higher RMET scores were associated with reduced N400 for both types of metaphors and with an earlier neural differentiation between metaphor types. Here, we tested whether these ToM-dependent neural dynamics can be reproduced using predictive measures from large language models (LLMs).
  To quantify the expectedness of each metaphor vehicle, we computed surprisal (the negative log probability of a word given its preceding context) from six LLMs. We extracted surprisal layer by layer, allowing us to test at which representational depth the model’s internal probability aligns with humans, and we calculated correlations with the EEG amplitude across the 200–1000 ms window.
  Results revealed a different patterns depending on ToM. In high-ToM individuals, the correlation between surprisal and the EEG amplitude emerged between 200–400 ms, a time window consistent with predictive contextual integration. In low-ToM individuals, the same relationship appeared between 600–1000 ms, consistent with global analysis processes. This difference is robust for physical metaphors. 
  These findings suggest that surprisal captures a dimension of contextual semantic fit that aligns with human neural processing, but only under specific cognitive conditions. High ToM ability is associated with a fast, expectancy-driven route to metaphor comprehension that mirrors the predictive structure encoded in model layers. Low ToM ability engages in a slower reanalysis route that relates to the same statistical signal but at a delayed latency.
  The absence of robust alignment for mental metaphors indicates that mental-state inference may rely on representational mechanisms that extend beyond what distributional language statistics alone can capture.


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2026-05-12'
# date_end: ''
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-09-13T00:00:00Z'

authors:
  - admin
  - Chiara Battaglini
  - Paolo Canal
  - Valentina Bambini

tags: [eeg, metaphors, theory of mind]

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