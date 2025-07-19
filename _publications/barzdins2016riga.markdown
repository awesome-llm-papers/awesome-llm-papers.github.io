---
layout: publication
title: 'RIGA At Semeval-2016 Task 8: Impact Of Smatch Extensions And Character-level
  Neural Translation On AMR Parsing Accuracy'
authors: Barzdins Guntis, Gosko Didzis
conference: Proceedings of the 10th International Workshop on Semantic Evaluation
  (SemEval-2016)
year: 2016
bibkey: barzdins2016riga
citations: 56
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1604.01278'}]
tags: [Evaluation]
---
Two extensions to the AMR smatch scoring script are presented. The first
extension com-bines the smatch scoring script with the C6.0 rule-based
classifier to produce a human-readable report on the error patterns frequency
observed in the scored AMR graphs. This first extension results in 4% gain over
the state-of-art CAMR baseline parser by adding to it a manually crafted
wrapper fixing the identified CAMR parser errors. The second extension combines
a per-sentence smatch with an en-semble method for selecting the best AMR graph
among the set of AMR graphs for the same sentence. This second modification
au-tomatically yields further 0.4% gain when ap-plied to outputs of two
nondeterministic AMR parsers: a CAMR+wrapper parser and a novel character-level
neural translation AMR parser. For AMR parsing task the character-level neural
translation attains surprising 7% gain over the carefully optimized word-level
neural translation. Overall, we achieve smatch F1=62% on the SemEval-2016
official scor-ing set and F1=67% on the LDC2015E86 test set.