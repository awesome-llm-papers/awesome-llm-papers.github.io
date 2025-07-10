---
layout: publication
title: 'One Chatbot Per Person: Creating Personalized Chatbots Based On Implicit User
  Profiles'
authors: Zhengyi Ma, Zhicheng Dou, Yutao Zhu, Hanxun Zhong, Ji-rong Wen
conference: 'SIGIR ''21: The 44th International ACM SIGIR Conference on Research and
  Development in Information Retrieval'
year: 2021
citations: 32
bibkey: ma2021one
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2108.09355'}, {name: Code,
    url: 'https://github.com/zhengyima/DHAP'}]
tags: [Has Code, Model Architecture, Transformer, RAG, Applications, Reinforcement
    Learning]
---
Personalized chatbots focus on endowing chatbots with a consistent
personality to behave like real users, give more informative responses, and
further act as personal assistants. Existing personalized approaches tried to
incorporate several text descriptions as explicit user profiles. However, the
acquisition of such explicit profiles is expensive and time-consuming, thus
being impractical for large-scale real-world applications. Moreover, the
restricted predefined profile neglects the language behavior of a real user and
cannot be automatically updated together with the change of user interests. In
this paper, we propose to learn implicit user profiles automatically from
large-scale user dialogue history for building personalized chatbots.
Specifically, leveraging the benefits of Transformer on language understanding,
we train a personalized language model to construct a general user profile from
the user's historical responses. To highlight the relevant historical responses
to the input post, we further establish a key-value memory network of
historical post-response pairs, and build a dynamic post-aware user profile.
The dynamic profile mainly describes what and how the user has responded to
similar posts in history. To explicitly utilize users' frequently used words,
we design a personalized decoder to fuse two decoding strategies, including
generating a word from the generic vocabulary and copying one word from the
user's personalized vocabulary. Experiments on two real-world datasets show the
significant improvement of our model compared with existing methods. Our code
is available at https://github.com/zhengyima/DHAP