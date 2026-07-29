---
title: What Drives Theory of Mind? Comparing the Role of ToM and Pragmatic Training Across Humans and Computational Models.

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
  The relationship between pragmatics and Theory of Mind (ToM) has been actively debated in the linguistic literature (Bambini and Lecce, 2025), yet largely overlooked in the computational field, despite growing interest in assessing both abilities in language models (Hu et al., 2024). Computational investigation of ToM has begun to draw on the formal definition introduced by Hu et al. (2025), and a growing body of work has attempted to isolate ToM reasoning in both evaluation and training, with the aim of assessing whether models “have” ToM.
  In this work, we support the view that pragmatics and ToM only partially overlap, as evidenced by psycholinguistic (Bosco et al., 2018) and neurolinguistic (Schieche and Uddén, 2025) research, and argue that this partial overlap makes it particularly important to investigate how ToM-like abilities emerge in models and how they can be disentangled from pragmatic competence. To examine this interaction, we fine-tune models on two distinct types of training material (ToM-specific and pragmatic) and apply causal analysis to determine which contributes more to performance on ToM and pragmatic tasks. We further compare these findings with human data evaluated under the same criteria, in order to assess whether pragmatic and ToM training play analogous roles in humans and models.
  We adopt the Llama-3-8B base architecture and conduct two supervised fine-tuning (SFT) procedures, one on pragmatic data and one on ToM-specific data, followed by Direct Preference Optimization (DPO) for each condition, maintaining a strict separation between pragmatic and ToM training materials across model variants. For ToM SFT, we use the Explore-ToM dataset (Sclar et al., 2024), which comprises narratives in which characters hold potentially divergent beliefs about the world and about one another's mental states, paired with questions probing nested belief reasoning. For pragmatic SFT, we use two synthetic reasoning datasets requiring general logical or factual inference rather than ToM reasoning. DPO is subsequently applied to each instruction-tuned model using preference datasets aligned with the corresponding training domain.To evaluate models before and after training, and to enable comparison with human training trajectories, we use the evaluation material of Del Sette et al. (2025), comprising the Physical and Mental Metaphors Task (PMM) for metaphor comprehension and the Strange Stories task (SS) for ToM. In the original study, children aged 8;9–9;10 were randomly assigned to either a ToM or a metaphor comprehension training condition (MetaCom). That work found that while both trainings produced improvements in their respective target measure, only MetaCom training produced a significant cross-domain effect on ToM, whereas ToM training did not enhance metaphor comprehension. This was taken to suggest a driving role of pragmatic-communicative competence in the development of advanced ToM, rather than the reverse. Comparing model performance on these same tasks with the results reported for humans in Del Sette et al. (2025) allows us to disentangle the respective contributions of pragmatic and ToM training, and to assess whether models replicate the asymmetric pattern observed in humans.
  Our results reveal three main distinctions between model and human training (see figures below). First, ToM training helps humans but consistently hurts models: after ToM SFT, model performance drops on both PMM (−0.041) and SS (−0.215), with SS collapsing entirely to zero under DPO (−0.286), while humans improve modestly on both tests (+0.030 PMM, +0.090 SS). Second, pragmatic training improves both humans and models, but with an inverted profile: under SFT, humans gain more on PMM (+0.130) than on SS (+0.065), while models gain dramatically more on SS (+0.571) than on PMM (+0.292). Under DPO, the asymmetry is even more pronounced for models: SS improves to near ceiling (+0.643) while PMM remains entirely unchanged (0.000), whereas human scores are stable across both tests under DPO. Third, SFT and DPO diverge specifically under pragmatic training for models: SFT improves both PMM and SS, whereas DPO selectively and dramatically improves SS while leaving PMM unaffected.
  Taken together, humans and models show an inverted profile across both training conditions: pragmatic training leads humans to gain more on the pragmatic measure (PMM) while models gain more on the ToM measure (SS); and ToM training produces improvements only in humans, while consistently hurting model performance.
  This dissociation points to a fundamental difference both in how pragmatic training generalizes across the two systems and in what counts as ToM training for models versus humans.
  Model ToM training targets a formal, computationally isolated capacity structured around decontextualized logical inference about mental states. Human ToM training, though nominally ToM-focused, is grounded in ecologically rich social scenarios integrating mental state reasoning with communicative intention, social norms, and pragmatic inference (placing it functionally closer to pragmatic than to formal ToM training). This mismatch would explain why humans improve after ToM training (their material was pragmatically rich enough to generalize across domains) while models deteriorate (EXPLORE optimizes a narrow formal capacity that may suppress the broader contextual processing needed for both PMM and SS). Crucially, this mismatch reveals that pragmatic scaffolding, rather than explicit ToM supervision, is what enables transferable ToM-like generalization in models, and that pure logical ToM optimization may be counterproductive. 
  More broadly, the results suggest that the architecture of ToM competence differs fundamentally between humans and current LLMs, with direct implications for how machine ToM should be trained and evaluated.
  We acknowledge that the training procedures are not directly comparable and that findings from a child sample have limited generalizability; we leave to future work the extension of the human comparison to adult populations and the exploration of the effects of exposing humans to computational ToM training material.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2026-09-24'
# date_end: ''
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-09-13T00:00:00Z'

authors:
  - admin
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
url_pdf: 'https://xpragit2026.weebly.com/'
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