---
layout: publication
title: 'Eurobert: Scaling Multilingual Encoders For European Languages'
authors: "Nicolas Boizard, Hippolyte Gisserot-boukhlef, Duarte M. Alves, Andr\xE9\
  \ Martins, Ayoub Hammal, Caio Corro, C\xE9line Hudelot, Emmanuel Malherbe, Etienne\
  \ Malaboeuf, Fanny Jourdan, Gabriel Hautreux, Jo\xE3o Alves, Kevin El-haddad, Manuel\
  \ Faysse, Maxime Peyrard, Nuno M. Guerreiro, Patrick Fernandes, Ricardo Rei, Pierre\
  \ Colombo"
conference: No Venue
year: 2025
bibkey: boizard2025eurobert
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/67ce9627e5cdfda52b9e88a4'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2503.05500'}]
tags: ["Datasets", "Tools", "Training Techniques"]
short_authors: Boizard et al.
---
General-purpose multilingual vector representations, used in retrieval, regression and classification, are traditionally obtained from bidirectional encoder models. Despite their wide applicability, encoders have been recently overshadowed by advances in generative decoder-only models. However, many innovations driving this progress are not inherently tied to decoders. In this paper, we revisit the development of multilingual encoders through the lens of these advances, and introduce EuroBERT, a family of multilingual encoders covering European and widely spoken global languages. Our models outperform existing alternatives across a diverse range of tasks, spanning multilingual capabilities, mathematics, and coding, and natively supporting sequences of up to 8,192 tokens. We also examine the design decisions behind EuroBERT, offering insights into our dataset composition and training pipeline. We publicly release the EuroBERT models, including intermediate training checkpoints, together with our training framework.

https://huggingface.co/discussions/paper/67ce9627e5cdfda52b9e88a4