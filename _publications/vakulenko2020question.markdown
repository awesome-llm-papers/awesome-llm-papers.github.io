---
layout: publication
title: Question Rewriting For Conversational Question Answering
authors: Svitlana Vakulenko, Shayne Longpre, Zhucheng Tu, Raviteja Anantha
conference: Proceedings of the 14th ACM International Conference on Web Search and
  Data Mining
year: 2021
bibkey: vakulenko2020question
citations: 129
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2004.14652'}]
tags: ["Datasets", "Evaluation", "Model Architecture"]
short_authors: Vakulenko et al.
---
Conversational question answering (QA) requires the ability to correctly
interpret a question in the context of previous conversation turns. We address
the conversational QA task by decomposing it into question rewriting and
question answering subtasks. The question rewriting (QR) subtask is
specifically designed to reformulate ambiguous questions, which depend on the
conversational context, into unambiguous questions that can be correctly
interpreted outside of the conversational context. We introduce a
conversational QA architecture that sets the new state of the art on the TREC
CAsT 2019 passage retrieval dataset. Moreover, we show that the same QR model
improves QA performance on the QuAC dataset with respect to answer span
extraction, which is the next step in QA after passage retrieval. Our
evaluation results indicate that the QR model we proposed achieves near
human-level performance on both datasets and the gap in performance on the
end-to-end conversational QA task is attributed mostly to the errors in QA.