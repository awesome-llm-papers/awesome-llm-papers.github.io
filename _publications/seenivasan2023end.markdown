---
layout: publication
title: 'Surgicalgpt: End-to-end Language-vision GPT For Visual Question Answering
  In Surgery'
authors: Lalithkumar Seenivasan, Mobarakol Islam, Gokul Kannan, Hongliang Ren
conference: Arxiv
year: 2023
citations: 18
bibkey: seenivasan2023end
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2304.09974'}]
tags: [GPT, Merging, RAG, Attention Mechanism, Model Architecture]
---
Advances in GPT-based large language models (LLMs) are revolutionizing
natural language processing, exponentially increasing its use across various
domains. Incorporating uni-directional attention, these autoregressive LLMs can
generate long and coherent paragraphs. However, for visual question answering
(VQA) tasks that require both vision and language processing, models with
bi-directional attention or models employing fusion techniques are often
employed to capture the context of multiple modalities all at once. As GPT does
not natively process vision tokens, to exploit the advancements in GPT models
for VQA in robotic surgery, we design an end-to-end trainable Language-Vision
GPT (LV-GPT) model that expands the GPT2 model to include vision input (image).
The proposed LV-GPT incorporates a feature extractor (vision tokenizer) and
vision token embedding (token type and pose). Given the limitations of
unidirectional attention in GPT models and their ability to generate coherent
long paragraphs, we carefully sequence the word tokens before vision tokens,
mimicking the human thought process of understanding the question to infer an
answer from an image. Quantitatively, we prove that the LV-GPT model
outperforms other state-of-the-art VQA models on two publically available
surgical-VQA datasets (based on endoscopic vision challenge robotic scene
segmentation 2018 and CholecTriplet2021) and on our newly annotated dataset
(based on the holistic surgical scene dataset). We further annotate all three
datasets to include question-type annotations to allow sub-type analysis.
Furthermore, we extensively study and present the effects of token sequencing,
token type and pose embedding for vision tokens in the LV-GPT model.