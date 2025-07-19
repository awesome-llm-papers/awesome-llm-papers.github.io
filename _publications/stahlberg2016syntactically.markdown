---
layout: publication
title: Syntactically Guided Neural Machine Translation
authors: Stahlberg et al.
conference: 'Proceedings of the 54th Annual Meeting of the Association for Computational
  Linguistics (Volume 2: Short Papers)'
year: 2016
bibkey: stahlberg2016syntactically
citations: 80
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1605.04569'}]
tags: [ACL]
---
We investigate the use of hierarchical phrase-based SMT lattices in
end-to-end neural machine translation (NMT). Weight pushing transforms the
Hiero scores for complete translation hypotheses, with the full translation
grammar score and full n-gram language model score, into posteriors compatible
with NMT predictive probabilities. With a slightly modified NMT beam-search
decoder we find gains over both Hiero and NMT decoding alone, with practical
advantages in extending NMT to very large input and output vocabularies.