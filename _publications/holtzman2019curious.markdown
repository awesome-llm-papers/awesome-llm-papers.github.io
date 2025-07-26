---
layout: publication
title: The Curious Case Of Neural Text Degeneration
authors: Ari Holtzman, Jan Buys, Li Du, Maxwell Forbes, Yejin Choi
conference: Arxiv
year: 2019
bibkey: holtzman2019curious
citations: 1194
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1904.09751'}]
tags: ["Training Techniques"]
short_authors: Holtzman et al.
---
Despite considerable advancements with deep neural language models, the
enigma of neural text degeneration persists when these models are tested as
text generators. The counter-intuitive empirical observation is that even
though the use of likelihood as training objective leads to high quality models
for a broad range of language understanding tasks, using likelihood as a
decoding objective leads to text that is bland and strangely repetitive.
  In this paper, we reveal surprising distributional differences between human
text and machine text. In addition, we find that decoding strategies alone can
dramatically effect the quality of machine text, even when generated from
exactly the same neural language model. Our findings motivate Nucleus Sampling,
a simple but effective method to draw the best out of neural generation. By
sampling text from the dynamic nucleus of the probability distribution, which
allows for diversity while effectively truncating the less reliable tail of the
distribution, the resulting text better demonstrates the quality of human text,
yielding enhanced diversity without sacrificing fluency and coherence.