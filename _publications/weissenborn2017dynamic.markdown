---
layout: publication
title: Dynamic Integration Of Background Knowledge In Neural NLU Systems
authors: "Dirk Weissenborn, Tom\xE1\u0161 Ko\u010Disk\xFD, Chris Dyer"
conference: Arxiv
year: 2017
bibkey: weissenborn2017dynamic
citations: 68
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1706.02596'}]
tags: ["Model Architecture", "Training Techniques"]
short_authors: "Dirk Weissenborn, Tom\xE1\u0161 Ko\u010Disk\xFD, Chris Dyer"
---
Common-sense and background knowledge is required to understand natural
language, but in most neural natural language understanding (NLU) systems, this
knowledge must be acquired from training corpora during learning, and then it
is static at test time. We introduce a new architecture for the dynamic
integration of explicit background knowledge in NLU models. A general-purpose
reading module reads background knowledge in the form of free-text statements
(together with task-specific text inputs) and yields refined word
representations to a task-specific NLU architecture that reprocesses the task
inputs with these representations. Experiments on document question answering
(DQA) and recognizing textual entailment (RTE) demonstrate the effectiveness
and flexibility of the approach. Analysis shows that our model learns to
exploit knowledge in a semantically appropriate way.