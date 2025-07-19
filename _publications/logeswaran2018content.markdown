---
layout: publication
title: Content Preserving Text Generation With Attribute Controls
authors: Logeswaran Lajanugen, Lee Honglak, Bengio Samy
conference: Arxiv
year: 2018
bibkey: logeswaran2018content
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1811.01135'}]
tags: [Language Modeling, Evaluation, Security]
---
In this work, we address the problem of modifying textual attributes of
sentences. Given an input sentence and a set of attribute labels, we attempt to
generate sentences that are compatible with the conditioning information. To
ensure that the model generates content compatible sentences, we introduce a
reconstruction loss which interpolates between auto-encoding and
back-translation loss components. We propose an adversarial loss to enforce
generated samples to be attribute compatible and realistic. Through
quantitative, qualitative and human evaluations we demonstrate that our model
is capable of generating fluent sentences that better reflect the conditioning
information compared to prior methods. We further demonstrate that the model is
capable of simultaneously controlling multiple attributes.