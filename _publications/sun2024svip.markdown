---
layout: publication
title: 'SVIP: Towards Verifiable Inference Of Open-source Large Language Models'
authors: Sun et al.
conference: SSRN Electronic Journal
year: 2024
bibkey: sun2024svip
citations: 99
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2410.22307'}]
tags: [Alt, Prompting, Security]
---
The ever-increasing size of open-source Large Language Models (LLMs) renders local deployment impractical for individual users. Decentralized computing has emerged as a cost-effective solution, allowing individuals and small companies to perform LLM inference for users using surplus computational power. However, a computing provider may stealthily substitute the requested LLM with a smaller, less capable model without consent from users, thereby benefiting from cost savings. We introduce SVIP, a secret-based verifiable LLM inference protocol. Unlike existing solutions based on cryptographic or game-theoretic techniques, our method is computationally effective and does not rest on strong assumptions. Our protocol requires the computing provider to return both the generated text and processed hidden representations from LLMs. We then train a proxy task on these representations, effectively transforming them into a unique model identifier. With our protocol, users can reliably verify whether the computing provider is acting honestly. A carefully integrated secret mechanism further strengthens its security. We thoroughly analyze our protocol under multiple strong and adaptive adversarial scenarios. Our extensive experiments demonstrate that SVIP is accurate, generalizable, computationally efficient, and resistant to various attacks. Notably, SVIP achieves false negative rates below 5% and false positive rates below 3%, while requiring less than 0.01 seconds per prompt query for verification.