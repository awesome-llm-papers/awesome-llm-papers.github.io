---
layout: publication
title: A Controlled Study On Long Context Extension And Generalization In Llms
authors: Yi Lu, Jing Nathan Yan, Songlin Yang, Justin T. Chiu, Siyu Ren, Fei Yuan,
  Wenting Zhao, Zhiyong Wu, Alexander M. Rush
conference: No Venue
year: 2024
bibkey: lu2024controlled
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/66eba4712f524b05fa0b1035'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2409.12181'}]
tags: ["In Context Learning", "Memory & Context"]
short_authors: Lu et al.
---
Broad textual understanding and in-context learning require language models that utilize full document contexts. Due to the implementation challenges associated with directly training long-context models, many methods have been proposed for extending models to handle long contexts. However, owing to differences in data and model classes, it has been challenging to compare these approaches, leading to uncertainty as to how to evaluate long-context performance and whether it differs from standard evaluation. We implement a controlled protocol for extension methods with a standardized evaluation, utilizing consistent base models and extension data. Our study yields several insights into long-context behavior. First, we reaffirm the critical role of perplexity as a general-purpose performance indicator even in longer-context tasks. Second, we find that current approximate attention methods systematically underperform across long-context tasks. Finally, we confirm that exact fine-tuning based methods are generally effective within the range of their extension, whereas extrapolation remains challenging. All codebases, models, and checkpoints will be made available open-source, promoting transparency and facilitating further research in this critical area of AI development.

https://huggingface.co/discussions/paper/66eba4712f524b05fa0b1035