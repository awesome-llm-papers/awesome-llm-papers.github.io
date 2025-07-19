---
layout: publication
title: Improving Question Generation With To The Point Context
authors: Li et al.
conference: Proceedings of the 2019 Conference on Empirical Methods in Natural Language
  Processing and the 9th International Joint Conference on Natural Language Processing
  (EMNLP-IJCNLP)
year: 2019
bibkey: li2019improving
citations: 51
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1910.06036'}]
tags: [RAG, Evaluation, EMNLP]
---
Question generation (QG) is the task of generating a question from a
reference sentence and a specified answer within the sentence. A major
challenge in QG is to identify answer-relevant context words to finish the
declarative-to-interrogative sentence transformation. Existing
sequence-to-sequence neural models achieve this goal by proximity-based answer
position encoding under the intuition that neighboring words of answers are of
high possibility to be answer-relevant. However, such intuition may not apply
to all cases especially for sentences with complex answer-relevant relations.
Consequently, the performance of these models drops sharply when the relative
distance between the answer fragment and other non-stop sentence words that
also appear in the ground truth question increases. To address this issue, we
propose a method to jointly model the unstructured sentence and the structured
answer-relevant relation (extracted from the sentence in advance) for question
generation. Specifically, the structured answer-relevant relation acts as the
to the point context and it thus naturally helps keep the generated question to
the point, while the unstructured sentence provides the full information.
Extensive experiments show that to the point context helps our question
generation model achieve significant improvements on several automatic
evaluation metrics. Furthermore, our model is capable of generating diverse
questions for a sentence which conveys multiple relations of its answer
fragment.