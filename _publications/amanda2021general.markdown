---
layout: publication
title: A General Language Assistant As A Laboratory For Alignment
authors: [amanda Askell, yuntao Bai, anna Chen, dawn Drain, deep Ganguli, tom Henighan,
  andy Jones, nicholas Joseph, ben Mann, nova Dassarma, nelson Elhage, zac Hatfield-dodds,
  danny Hernandez, jackson Kernion, kamal Ndousse, catherine Olsson, dario Amodei,
  tom Brown, jack Clark, sam Mccandlish, chris Olah, jared Kaplan]
conference: Arxiv
year: 2021
bibkey: amanda2021general
citations: 88
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2112.00861v3'}]
tags: ["Efficiency", "Training Techniques"]
short_authors: Askell et al.
---
Given the broad capabilities of large language models, it should be possible
to work towards a general-purpose, text-based assistant that is aligned with
human values, meaning that it is helpful, honest, and harmless. As an initial
foray in this direction we study simple baseline techniques and evaluations,
such as prompting. We find that the benefits from modest interventions increase
with model size, generalize to a variety of alignment evaluations, and do not
compromise the performance of large models. Next we investigate scaling trends
for several training objectives relevant to alignment, comparing imitation
learning, binary discrimination, and ranked preference modeling. We find that
ranked preference modeling performs much better than imitation learning, and
often scales more favorably with model size. In contrast, binary discrimination
typically performs and scales very similarly to imitation learning. Finally we
study a `preference model pre-training' stage of training, with the goal of
improving sample efficiency when finetuning on human preferences.