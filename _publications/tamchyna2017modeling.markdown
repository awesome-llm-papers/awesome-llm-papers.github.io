---
layout: publication
title: Modeling Target-side Inflection In Neural Machine Translation
authors: "Ale\u0161 Tamchyna, Marion Weller-di Marco, Alexander Fraser"
conference: Proceedings of the Second Conference on Machine Translation
year: 2017
bibkey: tamchyna2017modeling
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1707.06012'}]
tags: ["Training Techniques"]
short_authors: "Ale\u0161 Tamchyna, Marion Weller-di Marco, Alexander Fraser"
---
NMT systems have problems with large vocabulary sizes. Byte-pair encoding
(BPE) is a popular approach to solving this problem, but while BPE allows the
system to generate any target-side word, it does not enable effective
generalization over the rich vocabulary in morphologically rich languages with
strong inflectional phenomena. We introduce a simple approach to overcome this
problem by training a system to produce the lemma of a word and its
morphologically rich POS tag, which is then followed by a deterministic
generation step. We apply this strategy for English-Czech and English-German
translation scenarios, obtaining improvements in both settings. We furthermore
show that the improvement is not due to only adding explicit morphological
information.