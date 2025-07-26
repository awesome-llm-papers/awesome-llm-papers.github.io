---
layout: publication
title: 'The AMU-UEDIN Submission To The WMT16 News Translation Task: Attention-based
  NMT Models As Feature Functions In Phrase-based SMT'
authors: Marcin Junczys-dowmunt, Tomasz Dwojak, Rico Sennrich
conference: 'Proceedings of the First Conference on Machine Translation: Volume 2,
  Shared Task Papers'
year: 2016
bibkey: junczysdowmunt2016amu
citations: 66
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1605.04809'}]
tags: ["Evaluation"]
short_authors: Marcin Junczys-dowmunt, Tomasz Dwojak, Rico Sennrich
---
This paper describes the AMU-UEDIN submissions to the WMT 2016 shared task on
news translation. We explore methods of decode-time integration of
attention-based neural translation models with phrase-based statistical machine
translation. Efficient batch-algorithms for GPU-querying are proposed and
implemented. For English-Russian, our system stays behind the state-of-the-art
pure neural models in terms of BLEU. Among restricted systems, manual
evaluation places it in the first cluster tied with the pure neural model. For
the Russian-English task, our submission achieves the top BLEU result,
outperforming the best pure neural system by 1.1 BLEU points and our own
phrase-based baseline by 1.6 BLEU. After manual evaluation, this system is the
best restricted system in its own cluster. In follow-up experiments we improve
results by additional 0.8 BLEU.