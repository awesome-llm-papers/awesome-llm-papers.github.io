---
layout: publication
title: Added Toxicity Mitigation At Inference Time For Multimodal And Massively Multilingual
  Translation
authors: "Costa-juss\xE0 et al."
conference: Proceedings of the 2019 Conference of the North
year: 2023
bibkey: "costajuss\xE02023added"
citations: 81
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2311.06532'}]
tags: [Multimodal Models]
---
Added toxicity in the context of translation refers to the fact of producing
a translation output with more toxicity than there exists in the input. In this
paper, we present MinTox which is a novel pipeline to identify added toxicity
and mitigate this issue which works at inference time. MinTox uses a toxicity
detection classifier which is multimodal (speech and text) and works in
languages at scale. The mitigation method is applied to languages at scale and
directly in text outputs. MinTox is applied to SEAMLESSM4T, which is the latest
multimodal and massively multilingual machine translation system. For this
system, MinTox achieves significant added toxicity mitigation across domains,
modalities and language directions. MinTox manages to approximately filter out
from 25% to 95% of added toxicity (depending on the modality and domain) while
keeping translation quality.