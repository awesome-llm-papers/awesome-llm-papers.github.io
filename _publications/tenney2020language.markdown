---
layout: publication
title: 'The Language Interpretability Tool: Extensible, Interactive Visualizations
  And Analysis For NLP Models'
authors: Ian Tenney et al.
conference: 'Proceedings of the 2020 Conference on Empirical Methods in Natural Language
  Processing: System Demonstrations'
year: 2020
citations: 57
bibkey: tenney2020language
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2008.05122'}, {name: Code,
    url: 'https://github.com/pair-code/lit'}]
tags: [Language Modeling, Has Code, Ethics and Bias, Fine-Tuning, Interpretability
    and Explainability, Tools, Reinforcement Learning]
---
We present the Language Interpretability Tool (LIT), an open-source platform
for visualization and understanding of NLP models. We focus on core questions
about model behavior: Why did my model make this prediction? When does it
perform poorly? What happens under a controlled change in the input? LIT
integrates local explanations, aggregate analysis, and counterfactual
generation into a streamlined, browser-based interface to enable rapid
exploration and error analysis. We include case studies for a diverse set of
workflows, including exploring counterfactuals for sentiment analysis,
measuring gender bias in coreference systems, and exploring local behavior in
text generation. LIT supports a wide range of models--including classification,
seq2seq, and structured prediction--and is highly extensible through a
declarative, framework-agnostic API. LIT is under active development, with code
and full documentation available at https://github.com/pair-code/lit.