---
layout: publication
title: Adversarial Example Generation With Syntactically Controlled Paraphrase Networks
authors: Mohit Iyyer, John Wieting, Kevin Gimpel, Luke Zettlemoyer
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 1
  (Long Papers)'
year: 2018
bibkey: iyyer2018adversarial
citations: 623
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1804.06059'}]
tags: ["Security", "Training Techniques"]
short_authors: Iyyer et al.
---
We propose syntactically controlled paraphrase networks (SCPNs) and use them
to generate adversarial examples. Given a sentence and a target syntactic form
(e.g., a constituency parse), SCPNs are trained to produce a paraphrase of the
sentence with the desired syntax. We show it is possible to create training
data for this task by first doing backtranslation at a very large scale, and
then using a parser to label the syntactic transformations that naturally occur
during this process. Such data allows us to train a neural encoder-decoder
model with extra inputs to specify the target syntax. A combination of
automated and human evaluations show that SCPNs generate paraphrases that
follow their target specifications without decreasing paraphrase quality when
compared to baseline (uncontrolled) paraphrase systems. Furthermore, they are
more capable of generating syntactically adversarial examples that both (1)
"fool" pretrained models and (2) improve the robustness of these models to
syntactic variation when used to augment their training data.