---
layout: publication
title: 'PAINT: Paying Attention To Informed Tokens To Mitigate Hallucination In Large
  Vision-language Model'
authors: Arif et al.
conference: Proceedings of the 2023 Conference on Empirical Methods in Natural Language
  Processing
year: 2025
bibkey: arif2025paint
citations: 136
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2501.12206'}]
tags: [EMNLP, Attention Mechanism, Tools, Evaluation, Transformer, Model Architecture,
  Multimodal Models, Datasets]
---
Large Vision Language Models (LVLMs) have demonstrated remarkable
capabilities in understanding and describing visual content, achieving
state-of-the-art performance across various vision-language tasks. However,
these models often generate descriptions containing objects or details that are
absent in the input image, a phenomenon commonly known as hallucination. Our
work investigates the key reasons behind this issue by analyzing the pattern of
self-attention in transformer layers. We find that hallucinations often arise
from the progressive weakening of attention weight to visual tokens in the
deeper layers of the LLM. Some previous works naively boost the attention of
all visual tokens to mitigate this issue, resulting in suboptimal hallucination
reduction. To address this, we identify two critical sets of visual tokens that
facilitate the transfer of visual information from the vision encoder to the
LLM. Local tokens encode grounded information about objects present in an
image, while summary tokens capture the overall aggregated representation of
the image. Importantly, these two sets of tokens require different levels of
weight enhancement. To this end, we propose \textbf\{PAINT\} (\textbf\{P\}aying
\textbf\{A\}ttention to \textbf\{IN\}formed \textbf\{T\}okens), a plug-and-play
framework that intervenes in the self-attention mechanism of the LLM,
selectively boosting the attention weights of local and summary tokens with
experimentally learned margins. Evaluation on the MSCOCO image captioning
dataset demonstrate that our approach reduces hallucination rates by up to
62.3% compared to baseline models while maintaining accuracy. Code is
available at
\href\{https://github.com/hasanar1f/PAINT\}\{https://github.com/hasanar1f/PAINT\}