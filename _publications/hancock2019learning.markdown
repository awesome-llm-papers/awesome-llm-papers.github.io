---
layout: publication
title: 'Learning From Dialogue After Deployment: Feed Yourself, Chatbot!'
authors: "Braden Hancock, Antoine Bordes, Pierre-emmanuel Mazar\xE9, Jason Weston"
conference: Proceedings of the 57th Annual Meeting of the Association for Computational
  Linguistics
year: 2019
citations: 63
bibkey: hancock2019learning
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1901.05415'}]
tags: [Agentic, Training Techniques]
---
The majority of conversations a dialogue agent sees over its lifetime occur
after it has already been trained and deployed, leaving a vast store of
potential training signal untapped. In this work, we propose the self-feeding
chatbot, a dialogue agent with the ability to extract new training examples
from the conversations it participates in. As our agent engages in
conversation, it also estimates user satisfaction in its responses. When the
conversation appears to be going well, the user's responses become new training
examples to imitate. When the agent believes it has made a mistake, it asks for
feedback; learning to predict the feedback that will be given improves the
chatbot's dialogue abilities further. On the PersonaChat chit-chat dataset with
over 131k training examples, we find that learning from dialogue with a
self-feeding chatbot significantly improves performance, regardless of the
amount of traditional supervision.