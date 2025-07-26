---
layout: publication
title: 'LLM2CLIP: Powerful Language Model Unlock Richer Visual Representation'
authors: Weiquan Huang, Aoqi Wu, Yifan Yang, Xufang Luo, Yuqing Yang, Liang Hu, Qi
  Dai, Xiyang Dai, Dongdong Chen, Chong Luo, Lili Qiu
conference: No Venue
year: 2024
bibkey: huang2024llm2clip
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/6731dc4921823ee4ea35fcc1'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2411.04997'}]
tags: ["Efficiency", "Fine-Tuning", "Model Architecture", "Training Techniques"]
short_authors: Huang et al.
---
CLIP is one of the most important multimodal foundational models today. What powers CLIP's capabilities? The rich supervision signals provided by natural language, the carrier of human knowledge, shape a powerful cross-modal representation space. However, with the rapid advancements in large language models LLMs like GPT-4 and LLaMA, the boundaries of language comprehension and generation are continually being pushed. This raises an intriguing question: can the capabilities of LLMs be harnessed to further improve multimodal representation learning? The potential benefits of incorporating LLMs into CLIP are clear. LLMs' strong textual understanding can fundamentally improve CLIP's ability to handle image captions, drastically enhancing its ability to process long and complex texts, a well-known limitation of vanilla CLIP. Moreover, LLMs are trained on a vast corpus of text, possessing open-world knowledge. This allows them to expand on caption information during training, increasing the efficiency of the learning process. In this paper, we propose LLM2CLIP, a novel approach that embraces the power of LLMs to unlock CLIP's potential. By fine-tuning the LLM in the caption space with contrastive learning, we extract its textual capabilities into the output embeddings, significantly improving the output layer's textual discriminability. We then design an efficient training process where the fine-tuned LLM acts as a powerful teacher for CLIP's visual encoder. Thanks to the LLM's presence, we can now incorporate longer and more complex captions without being restricted by vanilla CLIP's text encoder's context window and ability limitations. Our experiments demonstrate that this approach brings substantial improvements in cross-modal tasks.

https://huggingface.co/discussions/paper/6731dc4921823ee4ea35fcc1