---
layout: publication
title: Domain Robustness In Neural Machine Translation
authors: "M\xFCller Mathias, Rios Annette, Sennrich Rico"
conference: Arxiv
year: 2019
bibkey: "m\xFCller2019domain"
citations: 58
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1911.03109'}]
tags: [Training Techniques, Evaluation, Security]
---
Translating text that diverges from the training domain is a key challenge
for machine translation. Domain robustness---the generalization of models to
unseen test domains---is low for both statistical (SMT) and neural machine
translation (NMT). In this paper, we study the performance of SMT and NMT
models on out-of-domain test sets. We find that in unknown domains, SMT and NMT
suffer from very different problems: SMT systems are mostly adequate but not
fluent, while NMT systems are mostly fluent, but not adequate. For NMT, we
identify such hallucinations (translations that are fluent but unrelated to the
source) as a key reason for low domain robustness. To mitigate this problem, we
empirically compare methods that are reported to improve adequacy or in-domain
robustness in terms of their effectiveness at improving domain robustness. In
experiments on German to English OPUS data, and German to Romansh (a
low-resource setting) we find that several methods improve domain robustness.
While those methods do lead to higher BLEU scores overall, they only slightly
increase the adequacy of translations compared to SMT.