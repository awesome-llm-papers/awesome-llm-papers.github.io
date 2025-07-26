---
layout: publication
title: Constrained Language Models Yield Few-shot Semantic Parsers
authors: Richard Shin, Christopher H. Lin, Sam Thomson, Charles Chen, Subhro Roy,
  Emmanouil Antonios Platanios, Adam Pauls, Dan Klein, Jason Eisner, Benjamin van
  Durme
conference: Proceedings of the 2021 Conference on Empirical Methods in Natural Language
  Processing
year: 2021
bibkey: shin2021constrained
citations: 120
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2104.08768'}]
tags: ["EMNLP", "Few-Shot"]
short_authors: Shin et al.
---
We explore the use of large pretrained language models as few-shot semantic
parsers. The goal in semantic parsing is to generate a structured meaning
representation given a natural language input. However, language models are
trained to generate natural language. To bridge the gap, we use language models
to paraphrase inputs into a controlled sublanguage resembling English that can
be automatically mapped to a target meaning representation. Our results
demonstrate that with only a small amount of data and very little code to
convert into English-like representations, our blueprint for rapidly
bootstrapping semantic parsers leads to surprisingly effective performance on
multiple community tasks, greatly exceeding baseline methods also trained on
the same limited data.