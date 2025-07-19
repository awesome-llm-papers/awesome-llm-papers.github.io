---
layout: publication
title: Harnessing Generative Llms For Enhanced Financial Event Entity Extraction Performance
authors: Choi Soo-joon, Park Ji-jun
conference: Data Intelligence
year: 2025
bibkey: choi2025harnessing
citations: 63
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2504.14633'}]
tags: [Training Techniques, Evaluation, BERT, Model Architecture, Reinforcement Learning,
  Fine Tuning, Datasets]
---
Financial event entity extraction is a crucial task for analyzing market
dynamics and building financial knowledge graphs, yet it presents significant
challenges due to the specialized language and complex structures in financial
texts. Traditional approaches often rely on sequence labeling models, which can
struggle with long-range dependencies and the inherent complexity of extracting
multiple, potentially overlapping entities. Motivated by the advanced language
understanding and generative capabilities of Large Language Models (LLMs), we
propose a novel method that reframes financial event entity extraction as a
text-to-structured-output generation task. Our approach involves fine-tuning a
pre-trained LLM using Parameter-Efficient Fine-Tuning (PEFT) to directly
generate a structured representation, such as a JSON object, containing the
extracted entities and their precise character spans from the input text. We
evaluate our method on the challenging CCKS 2019 Financial Event Entity
Extraction dataset, comparing its performance against strong sequence labeling
baselines, including SEBERTNets and sebertNets. Experimental results
demonstrate that our generative LLM method achieves a new state-of-the-art F1
score on this benchmark, significantly outperforming previous methods. Through
detailed quantitative analysis across event types, entity types, and instance
complexity, as well as human evaluation, we show that our approach is more
effective at handling the nuances of financial text and extracting high-quality
entities. This work validates the potential of applying generative LLMs
directly to complex, domain-specific information extraction tasks requiring
structured output.