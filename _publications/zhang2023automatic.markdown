---
layout: publication
title: Automatic Generation Of Multiple-choice Questions
authors: Zhang Cheng
conference: Arxiv
year: 2023
bibkey: zhang2023automatic
citations: 112
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2303.14576'}]
tags: [Model Architecture, Tools, Training Techniques, Transformer]
---
Creating multiple-choice questions to assess reading comprehension of a given
article involves generating question-answer pairs (QAPs) and adequate
distractors. We present two methods to tackle the challenge of QAP generations:
(1) A deep-learning-based end-to-end question generation system based on T5
Transformer with Preprocessing and Postprocessing Pipelines (TP3). We use the
finetuned T5 model for our downstream task of question generation and improve
accuracy using a combination of various NLP tools and algorithms in
preprocessing and postprocessing to select appropriate answers and filter
undesirable questions. (2) A sequence-learning-based scheme to generate
adequate QAPs via meta-sequence representations of sentences. A meta-sequence
is a sequence of vectors comprising semantic and syntactic tags. we devise a
scheme called MetaQA to learn meta sequences from training data to form pairs
of a meta sequence for a declarative sentence and a corresponding interrogative
sentence. The TP3 works well on unseen data, which is complemented by MetaQA.
Both methods can generate well-formed and grammatically correct questions.
Moreover, we present a novel approach to automatically generate adequate
distractors for a given QAP. The method is a combination of part-of-speech
tagging, named-entity tagging, semantic-role labeling, regular expressions,
domain knowledge bases, word embeddings, word edit distance, WordNet, and other
algorithms.