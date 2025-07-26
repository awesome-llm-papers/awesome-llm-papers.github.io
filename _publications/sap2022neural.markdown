---
layout: publication
title: Neural Theory-of-mind? On The Limits Of Social Intelligence In Large Lms
authors: Maarten Sap, Ronan Lebras, Daniel Fried, Yejin Choi
conference: Proceedings of the 2022 Conference on Empirical Methods in Natural Language
  Processing
year: 2022
bibkey: sap2022neural
citations: 70
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2210.13312'}]
tags: ["EMNLP"]
short_authors: Sap et al.
---
Social intelligence and Theory of Mind (ToM), i.e., the ability to reason
about the different mental states, intents, and reactions of all people
involved, allow humans to effectively navigate and understand everyday social
interactions. As NLP systems are used in increasingly complex social
situations, their ability to grasp social dynamics becomes crucial. In this
work, we examine the open question of social intelligence and Theory of Mind in
modern NLP systems from an empirical and theory-based perspective. We show that
one of today's largest language models (GPT-3; Brown et al., 2020) lacks this
kind of social intelligence out-of-the box, using two tasks: SocialIQa (Sap et
al., 2019), which measures models' ability to understand intents and reactions
of participants of social interactions, and ToMi (Le et al., 2019), which
measures whether models can infer mental states and realities of participants
of situations. Our results show that models struggle substantially at these
Theory of Mind tasks, with well-below-human accuracies of 55% and 60% on
SocialIQa and ToMi, respectively. To conclude, we draw on theories from
pragmatics to contextualize this shortcoming of large language models, by
examining the limitations stemming from their data, neural architecture, and
training paradigms. Challenging the prevalent narrative that only scale is
needed, we posit that person-centric NLP approaches might be more effective
towards neural Theory of Mind.
  In our updated version, we also analyze newer instruction tuned and RLFH
models for neural ToM. We find that even ChatGPT and GPT-4 do not display
emergent Theory of Mind; strikingly even GPT-4 performs only 60% accuracy on
the ToMi questions related to mental states and realities.