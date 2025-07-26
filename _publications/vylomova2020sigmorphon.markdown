---
layout: publication
title: 'SIGMORPHON 2020 Shared Task 0: Typologically Diverse Morphological Inflection'
authors: Ekaterina Vylomova, Jennifer White, Elizabeth Salesky, Sabrina J. Mielke,
  Shijie Wu, Edoardo Ponti, Rowan Hall Maudslay, Ran Zmigrod, Josef Valvoda, Svetlana
  Toldova, Francis Tyers, Elena Klyachko, Ilya Yegorov, Natalia Krizhanovsky, Paula
  Czarnowska, Irene Nikkarinen, Andrew Krizhanovsky, Tiago Pimentel, Lucas Torroba
  Hennigen, Christo Kirov, Garrett Nicolai, Adina Williams, Antonios Anastasopoulos,
  Hilaria Cruz, Eleanor Chodroff, Ryan Cotterell, Miikka Silfverberg, Mans Hulden
conference: Proceedings of the 17th SIGMORPHON Workshop on Computational Research
  in Phonetics, Phonology, and Morphology
year: 2020
bibkey: vylomova2020sigmorphon
citations: 73
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2006.11572'}]
tags: ["Training Techniques"]
short_authors: Vylomova et al.
---
A broad goal in natural language processing (NLP) is to develop a system that
has the capacity to process any natural language. Most systems, however, are
developed using data from just one language such as English. The SIGMORPHON
2020 shared task on morphological reinflection aims to investigate systems'
ability to generalize across typologically distinct languages, many of which
are low resource. Systems were developed using data from 45 languages and just
5 language families, fine-tuned with data from an additional 45 languages and
10 language families (13 in total), and evaluated on all 90 languages. A total
of 22 systems (19 neural) from 10 teams were submitted to the task. All four
winning systems were neural (two monolingual transformers and two massively
multilingual RNN-based models with gated attention). Most teams demonstrate
utility of data hallucination and augmentation, ensembles, and multilingual
training for low-resource languages. Non-neural learners and manually designed
grammars showed competitive and even superior performance on some languages
(such as Ingrian, Tajik, Tagalog, Zarma, Lingala), especially with very limited
data. Some language families (Afro-Asiatic, Niger-Congo, Turkic) were
relatively easy for most systems and achieved over 90% mean accuracy while
others were more challenging.