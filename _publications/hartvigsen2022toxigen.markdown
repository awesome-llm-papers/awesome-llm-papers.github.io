---
layout: publication
title: 'Toxigen: A Large-scale Machine-generated Dataset For Adversarial And Implicit
  Hate Speech Detection'
authors: Thomas Hartvigsen, Saadia Gabriel, Hamid Palangi, Maarten Sap, Dipankar Ray,
  Ece Kamar
conference: 'Proceedings of the 60th Annual Meeting of the Association for Computational
  Linguistics (Volume 1: Long Papers)'
year: 2022
bibkey: hartvigsen2022toxigen
citations: 127
additional_links: [{name: Code, url: 'https://github.com/microsoft/ToxiGen'}, {name: Paper,
    url: 'https://arxiv.org/abs/2203.09509'}]
tags: ["Datasets", "Security"]
short_authors: Hartvigsen et al.
---
Toxic language detection systems often falsely flag text that contains
minority group mentions as toxic, as those groups are often the targets of
online hate. Such over-reliance on spurious correlations also causes systems to
struggle with detecting implicitly toxic language. To help mitigate these
issues, we create ToxiGen, a new large-scale and machine-generated dataset of
274k toxic and benign statements about 13 minority groups. We develop a
demonstration-based prompting framework and an adversarial
classifier-in-the-loop decoding method to generate subtly toxic and benign text
with a massive pretrained language model. Controlling machine generation in
this way allows ToxiGen to cover implicitly toxic text at a larger scale, and
about more demographic groups, than previous resources of human-written text.
We conduct a human evaluation on a challenging subset of ToxiGen and find that
annotators struggle to distinguish machine-generated text from human-written
language. We also find that 94.5% of toxic examples are labeled as hate speech
by human annotators. Using three publicly-available datasets, we show that
finetuning a toxicity classifier on our data improves its performance on
human-written data substantially. We also demonstrate that ToxiGen can be used
to fight machine-generated toxicity as finetuning improves the classifier
significantly on our evaluation subset. Our code and data can be found at
https://github.com/microsoft/ToxiGen.