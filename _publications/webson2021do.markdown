---
layout: publication
title: Do Prompt-based Models Really Understand The Meaning Of Their Prompts?
authors: Albert Webson, Ellie Pavlick
conference: 'Proceedings of the 2022 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies'
year: 2022
bibkey: webson2021do
citations: 148
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2109.01247'}]
tags: ["NAACL", "Prompting"]
short_authors: Albert Webson, Ellie Pavlick
---
Recently, a boom of papers has shown extraordinary progress in zero-shot and
few-shot learning with various prompt-based models. It is commonly argued that
prompts help models to learn faster in the same way that humans learn faster
when provided with task instructions expressed in natural language. In this
study, we experiment with over 30 prompt templates manually written for natural
language inference (NLI). We find that models learn just as fast with many
prompts that are intentionally irrelevant or even pathologically misleading as
they do with instructively "good" prompts. Further, such patterns hold even for
models as large as 175 billion parameters (Brown et al., 2020) as well as the
recently proposed instruction-tuned models which are trained on hundreds of
prompts (Sanh et al., 2022). That is, instruction-tuned models often produce
good predictions with irrelevant and misleading prompts even at zero shots. In
sum, notwithstanding prompt-based models' impressive improvement, we find
evidence of serious limitations that question the degree to which such
improvement is derived from models understanding task instructions in ways
analogous to humans' use of task instructions.