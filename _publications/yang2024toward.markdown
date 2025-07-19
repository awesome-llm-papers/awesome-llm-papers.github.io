---
layout: publication
title: Toward Automatic Relevance Judgment Using Vision--language Models For Image--text
  Retrieval Evaluation
authors: Yang Jheng-hong, Lin Jimmy
conference: Proceedings of the 26th annual international ACM SIGIR conference on Research
  and development in informaion retrieval
year: 2024
bibkey: yang2024toward
citations: 491
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2408.01363'}]
tags: [GPT, Evaluation, Ethics And Bias, Model Architecture, SIGIR, Applications]
---
Vision--Language Models (VLMs) have demonstrated success across diverse
applications, yet their potential to assist in relevance judgments remains
uncertain. This paper assesses the relevance estimation capabilities of VLMs,
including CLIP, LLaVA, and GPT-4V, within a large-scale \textit\{ad hoc\}
retrieval task tailored for multimedia content creation in a zero-shot fashion.
Preliminary experiments reveal the following: (1) Both LLaVA and GPT-4V,
encompassing open-source and closed-source visual-instruction-tuned Large
Language Models (LLMs), achieve notable Kendall's \\(\tau \sim 0.4\\) when compared
to human relevance judgments, surpassing the CLIPScore metric. (2) While
CLIPScore is strongly preferred, LLMs are less biased towards CLIP-based
retrieval systems. (3) GPT-4V's score distribution aligns more closely with
human judgments than other models, achieving a Cohen's \\(\kappa\\) value of around
0.08, which outperforms CLIPScore at approximately -0.096. These findings
underscore the potential of LLM-powered VLMs in enhancing relevance judgments.