---
layout: publication
title: Instruction Following Without Instruction Tuning
authors: John Hewitt, Nelson F. Liu, Percy Liang, Christopher D. Manning
conference: No Venue
year: 2024
bibkey: hewitt2024instruction
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2409.14254'}]
tags: ["Instruction Following"]
short_authors: Hewitt et al.
---
Instruction tuning commonly means finetuning a language model on instruction-response pairs. We discover two forms of adaptation (tuning) that are deficient compared to instruction tuning, yet still yield instruction following; we call this implicit instruction tuning. We first find that instruction-response pairs are not necessary: training solely on responses, without any corresponding instructions, yields instruction following. This suggests pretrained models have an instruction-response mapping which is revealed by teaching the model the desired distribution of responses. However, we then find it's not necessary to teach the desired distribution of responses: instruction-response training on narrow-domain data like poetry still leads to broad instruction-following behavior like recipe generation. In particular, when instructions are very different from those in the narrow finetuning domain, models' responses do not adhere to the style of the finetuning domain. To begin to explain implicit instruction tuning, we hypothesize that very simple changes to a language model's distribution yield instruction following. We support this by hand-writing a rule-based language model which yields instruction following in a product-of-experts with a pretrained model. The rules are to slowly increase the probability of ending the sequence, penalize repetition, and uniformly change 15 words' probabilities. In summary, adaptations made without being designed to yield instruction following can do so implicitly.

https://huggingface.co/discussions/paper/66f69c7719fa4bbc45250837