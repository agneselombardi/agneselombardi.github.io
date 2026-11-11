---
title: From Metaphors to the Subjective Experience of Psychosis: an AI-Based Natural Language Inference Approach

event: 4th Italian Computational Psychiatry Conference
event_url: 'https://comppsy.it/'

location: Milano, Lombardia (Italy)
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

abstract: |
 Communication deficits are common across psychiatric conditions [1,2], and standard scales for assessing psychotic symptom severity, such as the Positive and Negative Syndrome Scale (PANSS) [3], rely on language and communication. While effective for assessing general psychopathology, these scales overlook the subjective experience of patients, an aspect that may emerge more directly through language itself. The Inventory of Psychotic-Like Anomalous Self-Experiences (IPASE) [4] addresses this gap, assessing subjective experience across self-awareness and bodily dimensions. However, its 57 items make scoring time-consuming and effortful in clinical practice.
 We propose an AI-based method for automatically characterizing patients' subjective experience from spontaneous speech, using metaphor as an entry point. While metaphor comprehension is consistently impaired in schizophrenia [5], metaphor production continues to reflect how individuals conceptualize and communicate their lived experience [6]. We hypothesized that patients' metaphors could be systematically linked to specific dimensions IPASE dimensions, providing an automatic bridge between natural language and a validated phenomenological framework of psychotic experience. 
 We analyzed illness-related interviews from125 patients (89 diagnosed with schizophrenia, 36 with other psychotic disorders), isolating sentences containing metaphors previously annotated by experts. To automatically link these metaphors to the IPASE scale, we cast the scoring problem as a Natural Language Inference (NLI) task using a multilingual BERT model: each metaphor-containing sentence was treated as a premise, and each IPASE item as a hypothesis, with the model estimating the degree of entailment on a 0-1 scale. This framing generalizes across patients and metaphors without requiring item-specific training data, yielding an interpretable alignment score between each metaphor and clinical item. The resulting method automatically maps patients’ metaphors onto specific IPASE dimensions, providing clinicians with an interpretable score. 
 Preliminary analysis revealed systematic associations between IPASE macro-categories (and items) and specific metaphor source domains (the concrete area of experience used to explain a more abstract concept [7]), consistently scoring above 0.6. For example, experiences involving disturbances of consciousness were preferentially expressed through metaphors grounded in natural disasters (“cariche di pioggia”), whereas somatic self-experiences were more frequently conveyed through game- and sport-related metaphors (“la vita è una giostra”). These findings suggest that metaphor source domains can be used to predict which IPASE items are most likely to be clinically relevant for a given patient. 
 Ongoing work is validating the automatically derived scores against clinician IPASE ratings and examining whether metaphor-derived profiles also track symptom severity as measured by the PANSS. By linking spontaneous metaphor production to a validated phenomenological scale, this approach has the potential to provide clinicians with an automated, interpretable measure of subjective psychopathology, and may inform language-based rehabilitation by identifying the conceptual patterns through which patients represent and communicate their experience.



# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: '2026-11-12'
# date_end: ''
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2025-09-13T00:00:00Z'

authors:
  - admin
  - Ginevra Martinelli
  - Maddalena Bressler 
  - Carola Cappadonna 
  - Fortunata Romeo 
  - Biagio Scalingi 
  - Jacopo Sapienza 
  - Federico Frau 
  - Chiara Barattieri di San Pietro 
  - Matteo Tonna 
  - Cecilia Spallarossa 
  - Cristiano Nichini 
  - Marta Bosia 
  - Valentina Bambini1

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
# url_pdf: ''
# url_slides: 'https://slideshare.net'
# url_video: 'https://youtube.com'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
url_slides: https://unipiit-my.sharepoint.com/:p:/g/personal/a_lombardi19_studenti_unipi_it/IQAQXSpi6lDyS6qCYnALI6qKAT3bDzZ8LdH20YD0hKeP0HY?e=omc9qQ


# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
#   - example
---