---
layout: publication
title: 'Hyst: A Hybrid Approach For Flexible And Accurate Dialogue State Tracking'
authors: "Rahul Goel, Shachi Paul, Dilek Hakkani-t\xFCr"
conference: Interspeech 2019
year: 2019
bibkey: goel2019hyst
citations: 84
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1907.00883'}]
tags: ["INTERSPEECH"]
short_authors: "Rahul Goel, Shachi Paul, Dilek Hakkani-t\xFCr"
---
Recent works on end-to-end trainable neural network based approaches have
demonstrated state-of-the-art results on dialogue state tracking. The best
performing approaches estimate a probability distribution over all possible
slot values. However, these approaches do not scale for large value sets
commonly present in real-life applications and are not ideal for tracking slot
values that were not observed in the training set. To tackle these issues,
candidate-generation-based approaches have been proposed. These approaches
estimate a set of values that are possible at each turn based on the
conversation history and/or language understanding outputs, and hence enable
state tracking over unseen values and large value sets however, they fall short
in terms of performance in comparison to the first group. In this work, we
analyze the performance of these two alternative dialogue state tracking
methods, and present a hybrid approach (HyST) which learns the appropriate
method for each slot type. To demonstrate the effectiveness of HyST on a
rich-set of slot types, we experiment with the recently released MultiWOZ-2.0
multi-domain, task-oriented dialogue-dataset. Our experiments show that HyST
scales to multi-domain applications. Our best performing model results in a
relative improvement of 24% and 10% over the previous SOTA and our best
baseline respectively.