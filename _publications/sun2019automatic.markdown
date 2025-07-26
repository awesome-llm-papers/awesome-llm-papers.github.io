---
layout: publication
title: Automatic Testing And Improvement Of Machine Translation
authors: Zeyu Sun, Jie M. Zhang, Mark Harman, Mike Papadakis, Lu Zhang
conference: Proceedings of the ACM/IEEE 42nd International Conference on Software
  Engineering
year: 2020
bibkey: sun2019automatic
citations: 102
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.02688'}]
tags: ["Evaluation"]
short_authors: Sun et al.
---
This paper presents TransRepair, a fully automatic approach for testing and
repairing the consistency of machine translation systems. TransRepair combines
mutation with metamorphic testing to detect inconsistency bugs (without access
to human oracles). It then adopts probability-reference or cross-reference to
post-process the translations, in a grey-box or black-box manner, to repair the
inconsistencies. Our evaluation on two state-of-the-art translators, Google
Translate and Transformer, indicates that TransRepair has a high precision
(99%) on generating input pairs with consistent translations. With these tests,
using automatic consistency metrics and manual assessment, we find that Google
Translate and Transformer have approximately 36% and 40% inconsistency bugs.
Black-box repair fixes 28% and 19% bugs on average for Google Translate and
Transformer. Grey-box repair fixes 30% bugs on average for Transformer. Manual
inspection indicates that the translations repaired by our approach improve
consistency in 87% of cases (degrading it in 2%), and that our repairs have
better translation acceptability in 27% of the cases (worse in 8%).