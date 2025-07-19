---
layout: publication
title: Reducing Large Language Model Safety Risks In Women's Health Using Semantic
  Entropy
authors: Penny-dimri et al.
conference: Nature
year: 2025
bibkey: pennydimri2025reducing
citations: 172
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2503.00269'}]
tags: [Alt, Responsible AI, Tools, Reinforcement Learning, Datasets]
---
Large language models (LLMs) hold substantial promise for clinical decision
support. However, their widespread adoption in medicine, particularly in
healthcare, is hindered by their propensity to generate false or misleading
outputs, known as hallucinations. In high-stakes domains such as women's health
(obstetrics & gynaecology), where errors in clinical reasoning can have
profound consequences for maternal and neonatal outcomes, ensuring the
reliability of AI-generated responses is critical. Traditional methods for
quantifying uncertainty, such as perplexity, fail to capture meaning-level
inconsistencies that lead to misinformation. Here, we evaluate semantic entropy
(SE), a novel uncertainty metric that assesses meaning-level variation, to
detect hallucinations in AI-generated medical content. Using a clinically
validated dataset derived from UK RCOG MRCOG examinations, we compared SE with
perplexity in identifying uncertain responses. SE demonstrated superior
performance, achieving an AUROC of 0.76 (95% CI: 0.75-0.78), compared to 0.62
(0.60-0.65) for perplexity. Clinical expert validation further confirmed its
effectiveness, with SE achieving near-perfect uncertainty discrimination
(AUROC: 0.97). While semantic clustering was successful in only 30% of cases,
SE remains a valuable tool for improving AI safety in women's health. These
findings suggest that SE could enable more reliable AI integration into
clinical practice, particularly in resource-limited settings where LLMs could
augment care. This study highlights the potential of SE as a key safeguard in
the responsible deployment of AI-driven tools in women's health, leading to
safer and more effective digital health interventions.