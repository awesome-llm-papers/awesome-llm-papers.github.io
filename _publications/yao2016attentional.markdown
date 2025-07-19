---
layout: publication
title: An Attentional Neural Conversation Model With Improved Specificity
authors: Yao et al.
conference: Proceedings of the AAAI Conference on Artificial Intelligence
year: 2016
bibkey: yao2016attentional
citations: 154
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1606.01292'}]
tags: [Model Architecture, Applications, AAAI, Attention Mechanism]
---
In this paper we propose a neural conversation model for conducting
dialogues. We demonstrate the use of this model to generate help desk
responses, where users are asking questions about PC applications. Our model is
distinguished by two characteristics. First, it models intention across turns
with a recurrent network, and incorporates an attention model that is
conditioned on the representation of intention. Secondly, it avoids generating
non-specific responses by incorporating an IDF term in the objective function.
The model is evaluated both as a pure generation model in which a help-desk
response is generated from scratch, and as a retrieval model with performance
measured using recall rates of the correct response. Experimental results
indicate that the model outperforms previously proposed neural conversation
architectures, and that using specificity in the objective function
significantly improves performances for both generation and retrieval.