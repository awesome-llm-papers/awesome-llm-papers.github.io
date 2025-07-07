---
layout: publication
title: 'DSTC8-AVSD: Multimodal Semantic Transformer Network With Retrieval Style Word
  Generator'
authors: Hwanhee Lee et al.
conference: Arxiv
year: 2020
citations: 15
bibkey: lee2020multimodal
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.08299'}]
tags: [Transformer, Attention Mechanism, Tools, Multimodal Models, Model Architecture]
---
Audio Visual Scene-aware Dialog (AVSD) is the task of generating a response
for a question with a given scene, video, audio, and the history of previous
turns in the dialog. Existing systems for this task employ the transformers or
recurrent neural network-based architecture with the encoder-decoder framework.
Even though these techniques show superior performance for this task, they have
significant limitations: the model easily overfits only to memorize the
grammatical patterns; the model follows the prior distribution of the
vocabularies in a dataset. To alleviate the problems, we propose a Multimodal
Semantic Transformer Network. It employs a transformer-based architecture with
an attention-based word embedding layer that generates words by querying word
embeddings. With this design, our model keeps considering the meaning of the
words at the generation stage. The empirical results demonstrate the
superiority of our proposed model that outperforms most of the previous works
for the AVSD task.