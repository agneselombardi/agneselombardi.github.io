---
title: Evaluating Conversational Implicatures in Large Language Models. Pragmatics or Theory of Mind?

event: LSA Annual Meeting
event_url: 'https://web.cvent.com/event/d453188a-a321-46d4-b57e-79d5067e6521/websitePage:0fce7914-bbae-47fb-991c-3050b18e5787'

location: New Orleans
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

abstract: |
  Recent advancements in Large Language Models (LLMs) have sparked growing interest in their ability to replicate human-like cognitive behaviors, particularly Theory of Mind (ToM)—the capacity to attribute beliefs, intentions, and perspectives to others (Premack & WoodruD, 1978). While LLMs display increasingly sophisticated linguistic performance (Wei et al., 2022), there is significant disagreement over whether such behavior genuinely reflects ToM abilities or results from advanced pattern recognition and pragmatic inference. A central issue is methodological: most ToM evaluations rely on behavioral tasks designed for humans, which may not accurately assess LLM-specific capabilities (Hu et al., 2025). Moreover, many of these tasks (e.g., the Strange Stories test) conflate pragmatic and ToM skills, making it diDicult to isolate mental-state reasoning (Bosco et al., 2018). We argue that, although behavioral methods have limitations, they can be repurposed to explore LLM cognition—if applied to carefully chosen phenomena and interpreted within a computational framework. In this study, we focus on conversational implicatures, identifying specific types that can be resolved through pragmatic competence alone, and others that appear to require intention attribution, hence implicating ToM. 
  We present a new dataset of 708 handcrafted items spanning eight types of conversational implicatures:
    1. Particularized Conversational Implicatures (PCI) – (Levinson, 1983).
        o A: What happened to the roast beef?
        o B: The dog is looking very happy.
    2. Generalized Conversational Implicatures (GCI) – (Levinson, 1983).
        o The water is warm.
    3. Indefinite Article – implications from "a/an" (Grice, 1975):
        o John walked into a house yesterday and saw a tortoise.
    4. Together Implications – plural subjects implying joint actions (Harnish, 1976):
        o "John and Jerry bought a piano."
    5. Coreference – pronoun/NP choices influence referential interpretation (Levinson, 2000):
        o "Jerry Rich came in. He walked to the window."
        o "Jerry Rich came in. The man walked to the window."
    6. Bridging – coherence-driven implications (Clark, 1977):
        o "John unpacked the picnic. The beer was warm."
    7. Indirect Speech Acts (ISAs) – utterances implying non-literal intentions (Austin, 1975; Searle, 1975):
        o "Do you know the time?"
    8. Informativeness Principle (I-Principle) – inferences based on informativeness (Levinson, 2000):
        o "He turned on the switch and the motor started."
  We compare LLM performance on these tasks with additional ToM-related phenomena: 64 false-belief tasks, 40 conventionalized indirect speech acts, and 24 irony tasks. Results are benchmarked against human responses from Prolific.
  Our analysis is guided by four research questions:
    1. Can ToM and pragmatic competence be dissociated in LLMs? We assess whether LLMs exhibit distinct patterns of performance on implicatures that do or do not require ToM, and compare this with performance on false-belief, irony, and indirect speech act tasks.
    2. How do LLM pragmatic and ToM abilities compare to human baselines? We evaluate whether model accuracy and reasoning strategies align with human interpretations.
    3. What do these results suggest about the presence (or absence) of ToM in LLMs?
    4. What are the implications for linguistic theories of ToM?


# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2026-01-08'
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
# slides: ""
# url_slides: https://unipiit-my.sharepoint.com/:p:/g/personal/a_lombardi19_studenti_unipi_it/EaP7YdWaVyhLgi3shfr0YAsB9U2QIWBn-Sn_Kx_3_8JtFw?e=JDiVuu&nav=eyJzSWQiOjI1NiwiY0lkIjozNzc3NzA5NDF9

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
#   - example
---