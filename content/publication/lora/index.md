---
title: "LoRA Training Provably Converges to a Low-Rank Global Minimum or It Fails Loudly (But it Probably Won't Fail)"
authors:
- Junsu Kim
- admin
- Ernest K. Ryu
author_notes:
date: "2025-02-15"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-02-15"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['preprint']

# Publication name and optional abbreviated publication name.
publication: "arXiv preprint"
publication_short: ""

abstract: Low-rank adaptation (LoRA) has become a standard approach for fine-tuning large foundation models. However, our theoretical understanding of LoRA remains limited as prior analyses of LoRA's training dynamics either rely on linearization arguments or consider highly simplified setups. In this work, we analyze the LoRA loss landscape without such restrictive assumptions. We define two regimes: a ``special regime'', which includes idealized setups where linearization arguments hold, and a ``generic regime'' representing more realistic setups where linearization arguments do not hold. In the generic regime, we show that LoRA training converges to a global minimizer with low rank and small magnitude, or a qualitatively distinct solution with high rank and large magnitude. Finally, we argue that the zero-initialization and weight decay in LoRA training induce an implicit bias toward the low-rank, small-magnitude region of the parameter space-where global minima lie-thus shedding light on why LoRA training usually succeeds in finding global minima.


# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'https://arxiv.org/abs/2502.09376'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
---
