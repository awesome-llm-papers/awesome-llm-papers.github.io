---
layout: publication
title: 'Plasticity Loss In Deep Reinforcement Learning: A Survey'
authors: Klein et al.
conference: IEEE Transactions on Neural Networks and Learning Systems
year: 2024
bibkey: klein2024plasticity
citations: 324
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.04832'}]
tags: [Training Techniques, Agentic, Evaluation, Ethics And Bias, Survey Paper, Reinforcement
    Learning, Fine Tuning, Merging]
---
Akin to neuroplasticity in human brains, the plasticity of deep neural
networks enables their quick adaption to new data. This makes plasticity
particularly crucial for deep Reinforcement Learning (RL) agents: Once
plasticity is lost, an agent's performance will inevitably plateau because it
cannot improve its policy to account for changes in the data distribution,
which are a necessary consequence of its learning process. Thus, developing
well-performing and sample-efficient agents hinges on their ability to remain
plastic during training. Furthermore, the loss of plasticity can be connected
to many other issues plaguing deep RL, such as training instabilities, scaling
failures, overestimation bias, and insufficient exploration. With this survey,
we aim to provide an overview of the emerging research on plasticity loss for
academics and practitioners of deep reinforcement learning. First, we propose a
unified definition of plasticity loss based on recent works, relate it to
definitions from the literature, and discuss metrics for measuring plasticity
loss. Then, we categorize and discuss numerous possible causes of plasticity
loss before reviewing currently employed mitigation strategies. Our taxonomy is
the first systematic overview of the current state of the field. Lastly, we
discuss prevalent issues within the literature, such as a necessity for broader
evaluation, and provide recommendations for future research, like gaining a
better understanding of an agent's neural activity and behavior.