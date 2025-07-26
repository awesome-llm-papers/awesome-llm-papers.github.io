---
layout: publication
title: Neural Machine Translation For Low-resource Languages
authors: "Robert \xD6stling, J\xF6rg Tiedemann"
conference: ACM Computing Surveys
year: 2022
bibkey: "\xF6stling2017neural"
citations: 171
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1708.05729'}]
tags: ["Survey Paper"]
short_authors: "Robert \xD6stling, J\xF6rg Tiedemann"
---
Neural machine translation (NMT) approaches have improved the state of the
art in many machine translation settings over the last couple of years, but
they require large amounts of training data to produce sensible output. We
demonstrate that NMT can be used for low-resource languages as well, by
introducing more local dependencies and using word alignments to learn sentence
reordering during translation. In addition to our novel model, we also present
an empirical evaluation of low-resource phrase-based statistical machine
translation (SMT) and NMT to investigate the lower limits of the respective
technologies. We find that while SMT remains the best option for low-resource
settings, our method can produce acceptable translations with only 70000 tokens
of training data, a level where the baseline NMT system fails completely.