---
layout: publication
title: Standing On The Shoulders Of Giant Frozen Language Models
authors: Yoav Levine et al.
conference: Arxiv
year: 2022
citations: 17
bibkey: levine2022standing
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2204.10019'}]
tags: [Fine-Tuning, RAG, Applications, Reinforcement Learning, Prompting, Training
    Techniques]
---
Huge pretrained language models (LMs) have demonstrated surprisingly good
zero-shot capabilities on a wide variety of tasks. This gives rise to the
appealing vision of a single, versatile model with a wide range of
functionalities across disparate applications. However, current leading
techniques for leveraging a "frozen" LM -- i.e., leaving its weights untouched
-- still often underperform fine-tuning approaches which modify these weights
in a task-dependent way. Those, in turn, suffer forgetfulness and compromise
versatility, suggesting a tradeoff between performance and versatility. The
main message of this paper is that current frozen-model techniques such as
prompt tuning are only the tip of the iceberg, and more powerful methods for
leveraging frozen LMs can do just as well as fine tuning in challenging domains
without sacrificing the underlying model's versatility. To demonstrate this, we
introduce three novel methods for leveraging frozen models: input-dependent
prompt tuning, frozen readers, and recursive LMs, each of which vastly improves
on current frozen-model approaches. Indeed, some of our methods even outperform
fine-tuning approaches in domains currently dominated by the latter. The
computational cost of each method is higher than that of existing frozen model
methods, but still negligible relative to a single pass through a huge frozen
LM. Each of these methods constitutes a meaningful contribution in its own
right, but by presenting these contributions together we aim to convince the
reader of a broader message that goes beyond the details of any given method:
that frozen models have untapped potential and that fine-tuning is often
unnecessary.