---
layout: publication
title: Gender Coreference And Bias Evaluation At WMT 2020
authors: Kocmi Tom, Limisiewicz Tomasz, Stanovsky Gabriel
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 2
  (Short Papers)'
year: 2020
bibkey: kocmi2020gender
citations: 94
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2010.06018'}]
tags: [ACL, Ethics And Bias, Reinforcement Learning, Evaluation]
---
Gender bias in machine translation can manifest when choosing gender
inflections based on spurious gender correlations. For example, always
translating doctors as men and nurses as women. This can be particularly
harmful as models become more popular and deployed within commercial systems.
Our work presents the largest evidence for the phenomenon in more than 19
systems submitted to the WMT over four diverse target languages: Czech, German,
Polish, and Russian. To achieve this, we use WinoMT, a recent automatic test
suite which examines gender coreference and bias when translating from English
to languages with grammatical gender. We extend WinoMT to handle two new
languages tested in WMT: Polish and Czech. We find that all systems
consistently use spurious correlations in the data rather than meaningful
contextual information.