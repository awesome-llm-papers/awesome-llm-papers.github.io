---
layout: publication
title: 'Reka Core, Flash, And Edge: A Series Of Powerful Multimodal Language Models'
authors: Aitor Ormazabal, Che Zheng, Cyprien de Masson D'autume, Dani Yogatama, Deyu
  Fu, Donovan Ong, Eric Chen, Eugenie Lamprecht, Hai Pham, Isaac Ong, Kaloyan Aleksiev,
  Lei Li, Matthew Henderson, Max Bain, Mikel Artetxe, Nishant Relan, Piotr Padlewski,
  Qi Liu, Ren Chen, Samuel Phua, Yazheng Yang, Yi Tay, Yuqi Wang, Zhongkai Zhu, Zhihui
  Xie
conference: No Venue
year: 2024
bibkey: ormazabal2024reka
additional_links: [{name: Code, url: 'http://chat.reka.ai'}, {name: Code, url: 'http://showcase.reka.ai'},
  {name: Code, url: 'https://huggingface.co/discussions/paper/6621c3e289877a1889e1e34a'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2404.12387'}]
tags: ["Evaluation Frameworks", "Evaluation", "Training Techniques"]
short_authors: Ormazabal et al.
---
We introduce Reka Core, Flash, and Edge, a series of powerful multimodal language models trained from scratch by Reka. Reka models are able to process and reason with text, images, video, and audio inputs. This technical report discusses details of training some of these models and provides comprehensive evaluation results. We show that Reka Edge and Reka Flash are not only state-of-the-art but also outperform many much larger models, delivering outsized values for their respective compute class. Meanwhile, our most capable and largest model, Reka Core, approaches the best frontier models on both automatic evaluations and blind human evaluations. On image question answering benchmarks (e.g. MMMU, VQAv2), Core performs competitively to GPT4-V. Meanwhile, on multimodal chat, Core ranks as the second most preferred model under a blind third-party human evaluation setup, outperforming other models such as Claude 3 Opus. On text benchmarks, Core not only performs competitively to other frontier models on a set of well-established benchmarks (e.g. MMLU, GSM8K) but also outperforms GPT4-0613 on human evaluation. On video question answering (Perception-Test), Core outperforms Gemini Ultra. Models are shipped in production at http://chat.reka.ai . A showcase of non cherry picked qualitative examples can also be found at http://showcase.reka.ai .

https://huggingface.co/discussions/paper/6621c3e289877a1889e1e34a