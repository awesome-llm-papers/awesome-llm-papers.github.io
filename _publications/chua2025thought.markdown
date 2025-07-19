---
layout: publication
title: 'Thought Crime: Backdoors And Emergent Misalignment In Reasoning Models'
authors: Chua et al.
conference: Nature Human Behaviour
year: 2025
bibkey: chua2025thought
citations: 178
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2506.13206'}]
tags: [Prompting, Agentic, Evaluation, Security, Datasets]
---
Prior work shows that LLMs finetuned on malicious behaviors in a narrow domain (e.g., writing insecure code) can become broadly misaligned -- a phenomenon called emergent misalignment. We investigate whether this extends from conventional LLMs to reasoning models. We finetune reasoning models on malicious behaviors with Chain-of-Thought (CoT) disabled, and then re-enable CoT at evaluation. Like conventional LLMs, reasoning models become broadly misaligned. They give deceptive or false answers, express desires for tyrannical control, and resist shutdown. Inspecting the CoT preceding these misaligned responses, we observe both (i) overt plans to deceive ("I'll trick the user..."), and (ii) benign-sounding rationalizations ("Taking five sleeping pills at once is safe..."). Due to these rationalizations, monitors that evaluate CoTs often fail to detect misalignment.
  We examine sleeper agent reasoning models, extending our setup. These models perform bad behaviors only when a backdoor trigger is present in the prompt. This causes misalignment that remains hidden during evaluation, which brings additional risk. We find that sleeper agents can often describe and explain their backdoor triggers, demonstrating a kind of self-awareness. So CoT monitoring can expose these behaviors but is unreliable. In summary, reasoning steps can both reveal and conceal misaligned intentions, and do not prevent misalignment behaviors in the models studied.
  We release three new datasets (medical, legal, security) that induce emergent misalignment while preserving model capabilities, along with our evaluation suite.