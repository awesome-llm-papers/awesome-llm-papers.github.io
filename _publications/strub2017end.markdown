---
layout: publication
title: End-to-end Optimization Of Goal-driven And Visually Grounded Dialogue Systems
authors: Florian Strub, Harm de Vries, Jeremie Mary, Bilal Piot, Aaron Courville,
  Olivier Pietquin
conference: Proceedings of the Twenty-Sixth International Joint Conference on Artificial
  Intelligence
year: 2017
bibkey: strub2017end
citations: 94
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1703.05423'}]
tags: ["IJCAI"]
short_authors: Strub et al.
---
End-to-end design of dialogue systems has recently become a popular research
topic thanks to powerful tools such as encoder-decoder architectures for
sequence-to-sequence learning. Yet, most current approaches cast human-machine
dialogue management as a supervised learning problem, aiming at predicting the
next utterance of a participant given the full history of the dialogue. This
vision is too simplistic to render the intrinsic planning problem inherent to
dialogue as well as its grounded nature, making the context of a dialogue
larger than the sole history. This is why only chit-chat and question answering
tasks have been addressed so far using end-to-end architectures. In this paper,
we introduce a Deep Reinforcement Learning method to optimize visually grounded
task-oriented dialogues, based on the policy gradient algorithm. This approach
is tested on a dataset of 120k dialogues collected through Mechanical Turk and
provides encouraging results at solving both the problem of generating natural
dialogues and the task of discovering a specific object in a complex picture.