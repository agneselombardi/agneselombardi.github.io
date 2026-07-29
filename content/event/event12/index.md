---
title: Large Language Models Encode Theory-of-Mind Individual Differences: Evidence from Neural Alignment During Metaphor Comprehension

event: Xprag-IT 2026
event_url: 'https://xpragit2026.weebly.com/'

location: Genova, Liguria (Italy)
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

abstract: |
 Metaphor comprehension has often been linked to Theory of Mind (ToM), particularly the case of mental metaphors. Individual differences in ToM have also been reported to modulate the N400, particularly with ToM-high individuals showing an earlier N400-like negativity to metaphor. Notably, in the language processing literature, the N400 is taken as a major index of surprisal and predictive processing, making metaphor comprehension a privileged window onto the interface between social cognition and linguistic prediction. 
 LLM surprisal has been shown to approximate ERP amplitudes, yet most work reduces it to a single final-layer estimate, discarding the rich internal structure of transformer networks. This is at odds with evidence that transformer layers encode distinct stages of processing, from surface lexical features in early layers to deep semantic and pragmatic integration in later ones, and that EEG signals align preferentially with specific depths rather than with final-layer output alone. 
 Moreover, instruction-tuned models have been shown to outperform base models on ToM tasks, an advantage that appears to be mediated by later layers specifically. If instruction tuning modulates ToM-relevant computation, we should be able to localise where in the network this happens and quantify how strongly it shapes the alignment with human neural data. 
 In this work, we bring these threads together by asking whether per-layer LLM surprisal can reproduce the ToM-dependent temporal dynamics of N400 responses during metaphor comprehension, and whether different model architectures and training regimes produce systematically different alignment profiles. We re-analysed the EEG dataset from [1], which recorded N400 responses to physical and mental metaphors and collected RMET scores as a measure of individual ToM ability. Participants were split into ToM-high and ToM-low groups based on the top and bottom thirds of the RMET distribution. Per-layer surprisal was extracted from six models: (Llama2-7B, Llama3-8B, Minerva-7B; each in base and instruction-tuned variants). For each model, surprisal was regressed onto EEG amplitude separately for each metaphor type and ToM group, across all layers and temporal lags.
 Significance was assessed via permutation test (p< .05), reporting combinations where the real correlation exceeded the random ones. 
 The results converge on several key findings. First, LLM surprisal successfully tracks the ToM-dependent temporal dynamics reported in [1], reproducing the neural dissociation in purely computational terms. Second, instruction tuning selectively modulated encoding for ToM-high participants processing physical metaphors, suggesting that the pragmatic representations shaped by instruction tuning are specifically relevant to how high-ToM individuals resolve physically grounded figurative language. Third, layer profiles varied substantially across model architectures, indicating that the depth at which ToM-relevant representations emerge is architecture-dependent.
 Taken together, these findings demonstrate that LLM surprisal does not merely reflect semantic difficulty, but tracks how that difficulty is resolved, and does so in ways that are sensitive to individual differences in social cognition. 
 This positions per-layer LLM surprisal as a fine-grained computational probe of the neurocognitive architecture underlying pragmatic language processing, and opens new avenues for using LLMs both to study individual differences in language and social cognition and to understand what underlying processing strategies humans are using.


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2026-09-29'
# date_end: ''
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-09-13T00:00:00Z'

authors:
  - admin
  - Chiara Battaglini
  - Paolo Canal
  - Valentina Bambini

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
url_pdf: 'https://2026.neurolang.org/'
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