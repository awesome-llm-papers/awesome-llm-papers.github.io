---
layout: publication
title: Dialogue History Matters! Personalized Response Selectionin Multi-turn Retrieval-based
  Chatbots
authors: Juntao Li et al.
conference: ACM Transactions on Information Systems
year: 2021
citations: 15
bibkey: li2021dialogue
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2103.09534'}]
tags: [Model Architecture, Attention Mechanism, Transformer, Applications, Reinforcement
    Learning]
---
Existing multi-turn context-response matching methods mainly concentrate on
obtaining multi-level and multi-dimension representations and better
interactions between context utterances and response. However, in real-place
conversation scenarios, whether a response candidate is suitable not only
counts on the given dialogue context but also other backgrounds, e.g., wording
habits, user-specific dialogue history content. To fill the gap between these
up-to-date methods and the real-world applications, we incorporate
user-specific dialogue history into the response selection and propose a
personalized hybrid matching network (PHMN). Our contributions are two-fold: 1)
our model extracts personalized wording behaviors from user-specific dialogue
history as extra matching information; 2) we perform hybrid representation
learning on context-response utterances and explicitly incorporate a customized
attention mechanism to extract vital information from context-response
interactions so as to improve the accuracy of matching. We evaluate our model
on two large datasets with user identification, i.e., personalized Ubuntu
dialogue Corpus (P-Ubuntu) and personalized Weibo dataset (P-Weibo).
Experimental results confirm that our method significantly outperforms several
strong models by combining personalized attention, wording behaviors, and
hybrid representation learning.