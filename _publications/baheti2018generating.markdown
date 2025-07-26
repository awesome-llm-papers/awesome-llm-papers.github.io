---
layout: publication
title: Generating More Interesting Responses In Neural Conversation Models With Distributional
  Constraints
authors: Ashutosh Baheti, Alan Ritter, Jiwei Li, Bill Dolan
conference: Proceedings of the 2018 Conference on Empirical Methods in Natural Language
  Processing
year: 2018
bibkey: baheti2018generating
citations: 99
additional_links: [{name: Code, url: 'https://github.com/abaheti95/DC-NeuralConversation'},
  {name: Paper, url: 'https://arxiv.org/abs/1809.01215'}]
tags: ["EMNLP"]
short_authors: Baheti et al.
---
Neural conversation models tend to generate safe, generic responses for most
inputs. This is due to the limitations of likelihood-based decoding objectives
in generation tasks with diverse outputs, such as conversation. To address this
challenge, we propose a simple yet effective approach for incorporating side
information in the form of distributional constraints over the generated
responses. We propose two constraints that help generate more content rich
responses that are based on a model of syntax and topics (Griffiths et al.,
2005) and semantic similarity (Arora et al., 2016). We evaluate our approach
against a variety of competitive baselines, using both automatic metrics and
human judgments, showing that our proposed approach generates responses that
are much less generic without sacrificing plausibility. A working demo of our
code can be found at https://github.com/abaheti95/DC-NeuralConversation.