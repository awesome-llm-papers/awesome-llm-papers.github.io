---
layout: publication
title: 'Lamda: Language Models For Dialog Applications'
authors: [romal Thoppilan, daniel de Freitas, jamie Hall, noam Shazeer, apoorv Kulshreshtha,
  heng-tze Cheng, alicia Jin, taylor Bos, leslie Baker, yu Du, yaguang Li, hongrae
    Lee, huaixiu Steven Zheng, amin Ghafouri, marcelo Menegali, yanping Huang, maxim
    Krikun, dmitry Lepikhin, james Qin, dehao Chen, yuanzhong Xu, zhifeng Chen, adam
    Roberts, maarten Bosma, vincent Zhao, yanqi Zhou, chung-ching Chang, igor Krivokon,
  will Rusch, marc Pickett, pranesh Srinivasan, laichee Man, kathleen Meier-hellstern,
  meredith Ringel Morris, tulsee Doshi, renelito Delos Santos, toju Duke, johnny Soraker,
  ben Zevenbergen, vinodkumar Prabhakaran, mark Diaz, ben Hutchinson, kristen Olson,
  alejandra Molina, erin Hoffman-john, josh Lee, lora Aroyo, ravi Rajakumar, alena
    Butryna, matthew Lamm, viktoriya Kuzmina, joe Fenton, aaron Cohen, rachel Bernstein,
  ray Kurzweil, blaise Aguera-arcas, claire Cui, marian Croak, ed Chi, quoc Le]
conference: Arxiv
year: 2022
bibkey: romal2022lamda
citations: 616
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2201.08239v3'}]
tags: ["Applications", "Model Architecture"]
short_authors: Thoppilan et al.
---
We present LaMDA: Language Models for Dialog Applications. LaMDA is a family
of Transformer-based neural language models specialized for dialog, which have
up to 137B parameters and are pre-trained on 1.56T words of public dialog data
and web text. While model scaling alone can improve quality, it shows less
improvements on safety and factual grounding. We demonstrate that fine-tuning
with annotated data and enabling the model to consult external knowledge
sources can lead to significant improvements towards the two key challenges of
safety and factual grounding. The first challenge, safety, involves ensuring
that the model's responses are consistent with a set of human values, such as
preventing harmful suggestions and unfair bias. We quantify safety using a
metric based on an illustrative set of human values, and we find that filtering
candidate responses using a LaMDA classifier fine-tuned with a small amount of
crowdworker-annotated data offers a promising approach to improving model
safety. The second challenge, factual grounding, involves enabling the model to
consult external knowledge sources, such as an information retrieval system, a
language translator, and a calculator. We quantify factuality using a
groundedness metric, and we find that our approach enables the model to
generate responses grounded in known sources, rather than responses that merely
sound plausible. Finally, we explore the use of LaMDA in the domains of
education and content recommendations, and analyze their helpfulness and role
consistency.