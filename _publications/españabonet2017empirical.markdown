---
layout: publication
title: An Empirical Analysis Of Nmt-derived Interlingual Embeddings And Their Use
  In Parallel Sentence Identification
authors: "Cristina Espa\xF1a-bonet, \xC1d\xE1m Csaba Varga, Alberto Barr\xF3n-cede\xF1\
  o, Josef van Genabith"
conference: IEEE Journal of Selected Topics in Signal Processing
year: 2017
bibkey: "espa\xF1abonet2017empirical"
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1704.05415'}]
tags: ["Evaluation", "Training Techniques"]
short_authors: "Espa\xF1a-bonet et al."
---
End-to-end neural machine translation has overtaken statistical machine
translation in terms of translation quality for some language pairs, specially
those with large amounts of parallel data. Besides this palpable improvement,
neural networks provide several new properties. A single system can be trained
to translate between many languages at almost no additional cost other than
training time. Furthermore, internal representations learned by the network
serve as a new semantic representation of words -or sentences- which, unlike
standard word embeddings, are learned in an essentially bilingual or even
multilingual context. In view of these properties, the contribution of the
present work is two-fold. First, we systematically study the NMT context
vectors, i.e. output of the encoder, and their power as an interlingua
representation of a sentence. We assess their quality and effectiveness by
measuring similarities across translations, as well as semantically related and
semantically unrelated sentence pairs. Second, as extrinsic evaluation of the
first point, we identify parallel sentences in comparable corpora, obtaining an
F1=98.2% on data from a shared task when using only NMT context vectors. Using
context vectors jointly with similarity measures F1 reaches 98.9%.