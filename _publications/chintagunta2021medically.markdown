---
layout: publication
title: Medically Aware GPT-3 As A Data Generator For Medical Dialogue Summarization
authors: Bharath Chintagunta, Namit Katariya, Xavier Amatriain, Anitha Kannan
conference: Proceedings of the Second Workshop on Natural Language Processing for
  Medical Conversations
year: 2021
bibkey: chintagunta2021medically
citations: 100
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2110.07356'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: Chintagunta et al.
---
In medical dialogue summarization, summaries must be coherent and must
capture all the medically relevant information in the dialogue. However,
learning effective models for summarization require large amounts of labeled
data which is especially hard to obtain. We present an algorithm to create
synthetic training data with an explicit focus on capturing medically relevant
information. We utilize GPT-3 as the backbone of our algorithm and scale 210
human labeled examples to yield results comparable to using 6400 human labeled
examples (~30x) leveraging low-shot learning and an ensemble method. In
detailed experiments, we show that this approach produces high quality training
data that can further be combined with human labeled data to get summaries that
are strongly preferable to those produced by models trained on human data alone
both in terms of medical accuracy and coherency.