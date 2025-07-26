---
layout: publication
title: Language Guided Local Infiltration For Interactive Image Retrieval
authors: Fuxiang Huang, Lei Zhang
conference: Arxiv
year: 2023
bibkey: huang2023language
citations: 133
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.07747'}]
tags: ["Evaluation", "Prompting"]
short_authors: Fuxiang Huang, Lei Zhang
---
Interactive Image Retrieval (IIR) aims to retrieve images that are generally
similar to the reference image but under the requested text modification. The
existing methods usually concatenate or sum the features of image and text
simply and roughly, which, however, is difficult to precisely change the local
semantics of the image that the text intends to modify. To solve this problem,
we propose a Language Guided Local Infiltration (LGLI) system, which fully
utilizes the text information and penetrates text features into image features
as much as possible. Specifically, we first propose a Language Prompt Visual
Localization (LPVL) module to generate a localization mask which explicitly
locates the region (semantics) intended to be modified. Then we introduce a
Text Infiltration with Local Awareness (TILA) module, which is deployed in the
network to precisely modify the reference image and generate image-text
infiltrated representation. Extensive experiments on various benchmark
databases validate that our method outperforms most state-of-the-art IIR
approaches.