---
layout: publication
title: 'Multimodal-gpt: A Vision And Language Model For Dialogue With Humans'
authors: Tao Gong et al.
conference: Arxiv
year: 2023
citations: 49
bibkey: gong2023multimodal
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2305.04790'}, {name: Code,
    url: 'https://github.com/open-mmlab/Multimodal-GPT'}]
tags: [Has Code, Model Architecture, Attention Mechanism, GPT, Transformer, Fine-Tuning,
  Multimodal Models, Training Techniques]
---
We present a vision and language model named MultiModal-GPT to conduct
multi-round dialogue with humans. MultiModal-GPT can follow various
instructions from humans, such as generating a detailed caption, counting the
number of interested objects, and answering general questions from users.
MultiModal-GPT is parameter-efficiently fine-tuned from OpenFlamingo, with
Low-rank Adapter (LoRA) added both in the cross-attention part and the
self-attention part of the language model. We first construct instruction
templates with vision and language data for multi-modality instruction tuning
to make the model understand and follow human instructions. We find the quality
of training data is vital for the dialogue performance, where few data
containing short answers can lead the model to respond shortly to any
instructions. To further enhance the ability to chat with humans of the
MultiModal-GPT, we utilize language-only instruction-following data to train
the MultiModal-GPT jointly. The joint training of language-only and
visual-language instructions with the *same* instruction template
effectively improves dialogue performance. Various demos show the ability of
continuous dialogue of MultiModal-GPT with humans. Code, dataset, and demo are
at https://github.com/open-mmlab/Multimodal-GPT