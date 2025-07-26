---
layout: publication
title: Visual Storytelling With Question-answer Plans
authors: Danyang Liu, Mirella Lapata, Frank Keller
conference: Arxiv
year: 2023
bibkey: liu2023visual
citations: 537
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.05295'}]
tags: ["Evaluation"]
short_authors: Danyang Liu, Mirella Lapata, Frank Keller
---
Visual storytelling aims to generate compelling narratives from image
sequences. Existing models often focus on enhancing the representation of the
image sequence, e.g., with external knowledge sources or advanced graph
structures. Despite recent progress, the stories are often repetitive,
illogical, and lacking in detail. To mitigate these issues, we present a novel
framework which integrates visual representations with pretrained language
models and planning. Our model translates the image sequence into a visual
prefix, a sequence of continuous embeddings which language models can
interpret. It also leverages a sequence of question-answer pairs as a blueprint
plan for selecting salient visual concepts and determining how they should be
assembled into a narrative. Automatic and human evaluation on the VIST
benchmark (Huang et al., 2016) demonstrates that blueprint-based models
generate stories that are more coherent, interesting, and natural compared to
competitive baselines and state-of-the-art systems.