---
layout: publication
title: Towards Unified Conversational Recommender Systems Via Knowledge-enhanced Prompt
  Learning
authors: [xiaolei Wang, kun Zhou, ji-rong Wen, wayne Xin Zhao]
conference: Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and
  Data Mining
year: 2022
bibkey: xiaolei2022towards
citations: 93
additional_links: [{name: Paper, url: 'http://arxiv.org/abs/2206.09363v1'}]
tags: ["KDD", "Prompting"]
short_authors: Wang et al.
---
Conversational recommender systems (CRS) aim to proactively elicit user
preference and recommend high-quality items through natural language
conversations. Typically, a CRS consists of a recommendation module to predict
preferred items for users and a conversation module to generate appropriate
responses. To develop an effective CRS, it is essential to seamlessly integrate
the two modules. Existing works either design semantic alignment strategies, or
share knowledge resources and representations between the two modules. However,
these approaches still rely on different architectures or techniques to develop
the two modules, making it difficult for effective module integration.
  To address this problem, we propose a unified CRS model named UniCRS based on
knowledge-enhanced prompt learning. Our approach unifies the recommendation and
conversation subtasks into the prompt learning paradigm, and utilizes
knowledge-enhanced prompts based on a fixed pre-trained language model (PLM) to
fulfill both subtasks in a unified approach. In the prompt design, we include
fused knowledge representations, task-specific soft tokens, and the dialogue
context, which can provide sufficient contextual information to adapt the PLM
for the CRS task. Besides, for the recommendation subtask, we also incorporate
the generated response template as an important part of the prompt, to enhance
the information interaction between the two subtasks. Extensive experiments on
two public CRS datasets have demonstrated the effectiveness of our approach.