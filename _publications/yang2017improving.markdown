---
layout: publication
title: Improving Neural Machine Translation With Conditional Sequence Generative Adversarial
  Nets
authors: Zhen Yang, Wei Chen, Feng Wang, Bo Xu
conference: 'Proceedings of the 2018 Conference of the North American Chapter of the
  Association for Computational Linguistics: Human Language Technologies, Volume 1
  (Long Papers)'
year: 2018
bibkey: yang2017improving
citations: 171
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1703.04887'}]
tags: ["Model Architecture", "NAACL", "Training Techniques"]
short_authors: Yang et al.
---
This paper proposes an approach for applying GANs to NMT. We build a
conditional sequence generative adversarial net which comprises of two
adversarial sub models, a generator and a discriminator. The generator aims to
generate sentences which are hard to be discriminated from human-translated
sentences (i.e., the golden target sentences), And the discriminator makes
efforts to discriminate the machine-generated sentences from human-translated
ones. The two sub models play a mini-max game and achieve the win-win situation
when they reach a Nash Equilibrium. Additionally, the static sentence-level
BLEU is utilized as the reinforced objective for the generator, which biases
the generation towards high BLEU points. During training, both the dynamic
discriminator and the static BLEU objective are employed to evaluate the
generated sentences and feedback the evaluations to guide the learning of the
generator. Experimental results show that the proposed model consistently
outperforms the traditional RNNSearch and the newly emerged state-of-the-art
Transformer on English-German and Chinese-English translation tasks.