---
layout: publication
title: 'Sdpo: Don''t Use Your Data All At Once'
authors: Dahyun Kim, Yungi Kim, Wonho Song, Hyeonwoo Kim, Yunsu Kim, Sanghoon Kim,
  Chanjun Park
conference: No Venue
year: 2024
bibkey: kim2024sdpo
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2403.19270'}]
tags: ["Datasets", "Efficiency", "Reinforcement Learning", "Tools", "Training Techniques"]
short_authors: Kim et al.
---
As development of large language models (LLM) progresses, aligning them with human preferences has become increasingly important. We propose stepwise DPO (sDPO), an extension of the recently popularized direct preference optimization (DPO) for alignment tuning. This approach involves dividing the available preference datasets and utilizing them in a stepwise manner, rather than employing it all at once. We demonstrate that this method facilitates the use of more precisely aligned reference models within the DPO training framework. Furthermore, sDPO trains the final model to be more performant, even outperforming other popular LLMs with more parameters.

https://huggingface.co/discussions/paper/6606447cf631d41ec45b1af7