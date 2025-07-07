---
layout: publication
title: 'DS-1000: A Natural And Reliable Benchmark For Data Science Code Generation'
authors: Yuhang Lai et al.
conference: Arxiv
year: 2022
citations: 15
bibkey: lai2022ds
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2211.11501'}, {name: Code,
    url: 'https://ds1000-code-gen.github.io'}]
tags: [Training Techniques, Pre-Training, Tools, Has Code, Applications]
---
We introduce DS-1000, a code generation benchmark with a thousand data
science problems spanning seven Python libraries, such as NumPy and Pandas.
Compared to prior works, DS-1000 incorporates three core features. First, our
problems reflect diverse, realistic, and practical use cases since we collected
them from StackOverflow. Second, our automatic evaluation is highly specific
(reliable) -- across all Codex-002-predicted solutions that our evaluation
accept, only 1.8% of them are incorrect; we achieve this with multi-criteria
metrics, checking both functional correctness by running test cases and
surface-form constraints by restricting API usages or keywords. Finally, we
proactively defend against memorization by slightly modifying our problems to
be different from the original StackOverflow source; consequently, models
cannot answer them correctly by memorizing the solutions from pre-training. The
current best public system (Codex-002) achieves 43.3% accuracy, leaving ample
room for improvement. We release our benchmark at
https://ds1000-code-gen.github.io.