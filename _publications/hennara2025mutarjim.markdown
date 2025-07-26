---
layout: publication
title: 'Mutarjim: Advancing Bidirectional Arabic-english Translation With A Small
  Language Model'
authors: Khalil Hennara, Muhammad Hreden, Mohamed Motaism Hamed, Zeina Aldallal, Sara
  Chrouf, Safwan Almodhayan
conference: No Venue
year: 2025
bibkey: hennara2025mutarjim
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2505.17894'}]
tags: ["Datasets", "Evaluation", "Model Architecture", "Tools", "Training Techniques"]
short_authors: Hennara et al.
---
We introduce Mutarjim, a compact yet powerful language model for bidirectional Arabic-English translation. While large-scale LLMs have shown impressive progress in natural language processing tasks, including machine translation, smaller models. Leveraging this insight, we developed Mutarjim based on Kuwain-1.5B , a language model tailored for both Arabic and English. Despite its modest size, Mutarjim outperforms much larger models on several established benchmarks, achieved through an optimized two-phase training approach and a carefully curated, high-quality training corpus.. Experimental results show that Mutarjim rivals models up to 20 times larger while significantly reducing computational costs and training requirements. We also introduce Tarjama-25, a new benchmark designed to overcome limitations in existing Arabic-English benchmarking datasets, such as domain narrowness, short sentence lengths, and English-source bias. Tarjama-25 comprises 5,000 expert-reviewed sentence pairs and spans a wide range of domains, offering a more comprehensive and balanced evaluation framework. Notably, Mutarjim achieves state-of-the-art performance on the English-to-Arabic task in Tarjama-25, surpassing even significantly larger and proprietary models like GPT-4o mini. We publicly release Tarjama-25 to support future research and advance the evaluation of Arabic-English translation systems.

https://huggingface.co/discussions/paper/683577dc7733c0f27e94588d