---
layout: publication
title: Fusion Of Detected Objects In Text For Visual Question Answering
authors: Chris Alberti, Jeffrey Ling, Michael Collins, David Reitter
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: alberti2019fusion
citations: 171
additional_links: [{name: Code, url: 'https://github.com/google-research/language/tree/master/language/question_answering/b2t2)'},
  {name: Paper, url: 'https://arxiv.org/abs/1908.05054'}]
tags: ["EMNLP", "Model Architecture"]
short_authors: Alberti et al.
---
To advance models of multimodal context, we introduce a simple yet powerful
neural architecture for data that combines vision and natural language. The
"Bounding Boxes in Text Transformer" (B2T2) also leverages referential
information binding words to portions of the image in a single unified
architecture. B2T2 is highly effective on the Visual Commonsense Reasoning
benchmark (https://visualcommonsense.com), achieving a new state-of-the-art
with a 25% relative reduction in error rate compared to published baselines and
obtaining the best performance to date on the public leaderboard (as of May 22,
2019). A detailed ablation analysis shows that the early integration of the
visual features into the text analysis is key to the effectiveness of the new
architecture. A reference implementation of our models is provided
(https://github.com/google-research/language/tree/master/language/question_answering/b2t2).