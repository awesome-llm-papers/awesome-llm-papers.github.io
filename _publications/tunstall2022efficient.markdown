---
layout: publication
title: Efficient Few-shot Learning Without Prompts
authors: Lewis Tunstall, Nils Reimers, Unso Eun Seo Jo, Luke Bates, Daniel Korat,
  Moshe Wasserblat, Oren Pereg
conference: Arxiv
year: 2022
bibkey: tunstall2022efficient
citations: 78
additional_links: [{name: Code, url: 'https://github.com/huggingface/setfit'}, {name: Code,
    url: 'https://huggingface.co/setfit'}, {name: Paper, url: 'https://arxiv.org/abs/2209.11055'}]
tags: ["Few-Shot"]
short_authors: Tunstall et al.
---
Recent few-shot methods, such as parameter-efficient fine-tuning (PEFT) and
pattern exploiting training (PET), have achieved impressive results in
label-scarce settings. However, they are difficult to employ since they are
subject to high variability from manually crafted prompts, and typically
require billion-parameter language models to achieve high accuracy. To address
these shortcomings, we propose SetFit (Sentence Transformer Fine-tuning), an
efficient and prompt-free framework for few-shot fine-tuning of Sentence
Transformers (ST). SetFit works by first fine-tuning a pretrained ST on a small
number of text pairs, in a contrastive Siamese manner. The resulting model is
then used to generate rich text embeddings, which are used to train a
classification head. This simple framework requires no prompts or verbalizers,
and achieves high accuracy with orders of magnitude less parameters than
existing techniques. Our experiments show that SetFit obtains comparable
results with PEFT and PET techniques, while being an order of magnitude faster
to train. We also show that SetFit can be applied in multilingual settings by
simply switching the ST body. Our code is available at
https://github.com/huggingface/setfit and our datasets at
https://huggingface.co/setfit .