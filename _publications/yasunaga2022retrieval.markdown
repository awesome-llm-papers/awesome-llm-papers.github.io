---
layout: publication
title: Retrieval-augmented Multimodal Language Modeling
authors: Michihiro Yasunaga et al.
conference: Arxiv
year: 2022
citations: 16
bibkey: yasunaga2022retrieval
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.12561'}]
tags: [Training Techniques, Transformer, RAG, In-Context Learning, Multimodal Models,
  Language Modeling, Model Architecture]
---
Recent multimodal models such as DALL-E and CM3 have achieved remarkable
progress in text-to-image and image-to-text generation. However, these models
store all learned knowledge (e.g., the appearance of the Eiffel Tower) in the
model parameters, requiring increasingly larger models and training data to
capture more knowledge. To integrate knowledge in a more scalable and modular
way, we propose a retrieval-augmented multimodal model, which enables a base
multimodal model (generator) to refer to relevant text and images fetched by a
retriever from external memory (e.g., documents on the web). Specifically, for
the retriever, we use a pretrained CLIP, and for the generator, we train a CM3
Transformer on the LAION dataset. Our resulting model, named
Retrieval-Augmented CM3 (RA-CM3), is the first multimodal model that can
retrieve and generate both text and images. We show that RA-CM3 significantly
outperforms baseline multimodal models such as DALL-E and CM3 on both image and
caption generation tasks (12 FID and 17 CIDEr improvements on MS-COCO), while
requiring much less compute for training (<30% of DALL-E). Moreover, we show
that RA-CM3 exhibits novel capabilities, such as faithful image generation and
multimodal in-context learning (e.g., image generation from demonstrations).