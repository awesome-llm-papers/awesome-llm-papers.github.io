---
layout: publication
title: 'Getting From Generative AI To Trustworthy AI: What Llms Might Learn From Cyc'
authors: Doug Lenat, Gary Marcus
conference: Arxiv
year: 2023
citations: 16
bibkey: lenat2023getting
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2308.04445'}]
tags: [Uncategorized]
---
Generative AI, the most popular current approach to AI, consists of large
language models (LLMs) that are trained to produce outputs that are plausible,
but not necessarily correct. Although their abilities are often uncanny, they
are lacking in aspects of reasoning, leading LLMs to be less than completely
trustworthy. Furthermore, their results tend to be both unpredictable and
uninterpretable.
  We lay out 16 desiderata for future AI, and discuss an alternative approach
to AI which could theoretically address many of the limitations associated with
current approaches: AI educated with curated pieces of explicit knowledge and
rules of thumb, enabling an inference engine to automatically deduce the
logical entailments of all that knowledge. Even long arguments produced this
way can be both trustworthy and interpretable, since the full step-by-step line
of reasoning is always available, and for each step the provenance of the
knowledge used can be documented and audited. There is however a catch: if the
logical language is expressive enough to fully represent the meaning of
anything we can say in English, then the inference engine runs much too slowly.
That's why symbolic AI systems typically settle for some fast but much less
expressive logic, such as knowledge graphs. We describe how one AI system, Cyc,
has developed ways to overcome that tradeoff and is able to reason in higher
order logic in real time.
  We suggest that any trustworthy general AI will need to hybridize the
approaches, the LLM approach and more formal approach, and lay out a path to
realizing that dream.