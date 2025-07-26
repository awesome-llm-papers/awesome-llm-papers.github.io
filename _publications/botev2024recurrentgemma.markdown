---
layout: publication
title: 'Recurrentgemma: Moving Past Transformers For Efficient Open Language Models'
authors: "Aleksandar Botev, Soham de, Samuel L Smith, Anushan Fernando, George-cristian\
  \ Muraru, Ruba Haroun, Leonard Berrada, Razvan Pascanu, Pier Giuseppe Sessa, Robert\
  \ Dadashi, L\xE9onard Hussenot, Johan Ferret, Sertan Girgin, Olivier Bachem, Alek\
  \ Andreev, Kathleen Kenealy, Thomas Mesnard, Cassidy Hardin, Surya Bhupatiraju,\
  \ Shreya Pathak, Laurent Sifre, Morgane Rivi\xE8re, Mihir Sanjay Kale, Juliette\
  \ Love, Pouya Tafti, Armand Joulin, Noah Fiedel, Evan Senter, Yutian Chen, Srivatsan\
  \ Srinivasan, Guillaume Desjardins, David Budden, Arnaud Doucet, Sharad Vikram,\
  \ Adam Paszke, Trevor Gale, Sebastian Borgeaud, Charlie Chen, Andy Brock, Antonia\
  \ Paterson, Jenny Brennan, Meg Risdal, Raj Gundluru, Nesh Devanathan, Paul Mooney,\
  \ Nilay Chauhan, Phil Culliton, Luiz Gustavo Martins, Elisa Bandy, David Huntsperger,\
  \ Glenn Cameron, Arthur Zucker, Tris Warkentin, Ludovic Peran, Minh Giang, Zoubin\
  \ Ghahramani, Cl\xE9ment Farabet, Koray Kavukcuoglu, Demis Hassabis, Raia Hadsell,\
  \ Yee Whye Teh, Nando de Frietas"
conference: No Venue
year: 2024
bibkey: botev2024recurrentgemma
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2404.07839'}]
tags: ["Model Architecture"]
short_authors: Botev et al.
---
We introduce RecurrentGemma, an open language model which uses Google's novel Griffin architecture. Griffin combines linear recurrences with local attention to achieve excellent performance on language. It has a fixed-sized state, which reduces memory use and enables efficient inference on long sequences. We provide a pre-trained model with 2B non-embedding parameters, and an instruction tuned variant. Both models achieve comparable performance to Gemma-2B despite being trained on fewer tokens.

https://huggingface.co/discussions/paper/661890a465e0419878fcb65d