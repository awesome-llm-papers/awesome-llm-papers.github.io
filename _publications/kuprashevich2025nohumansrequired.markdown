---
layout: publication
title: 'Nohumansrequired: Autonomous High-quality Image Editing Triplet Mining'
authors: Maksim Kuprashevich, Grigorii Alekseenko, Irina Tolstykh, Georgii Fedorov,
  Bulat Suleimanov, Vladimir Dokholyan, Aleksandr Gordeev
conference: No Venue
year: 2025
bibkey: kuprashevich2025nohumansrequired
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2507.14119'}]
tags: ["Datasets", "Evaluation", "Prompting", "Training Techniques"]
short_authors: Kuprashevich et al.
---
Recent advances in generative modeling enable image editing assistants that follow natural language instructions without additional user input. Their supervised training requires millions of triplets: original image, instruction, edited image. Yet mining pixel-accurate examples is hard. Each edit must affect only prompt-specified regions, preserve stylistic coherence, respect physical plausibility, and retain visual appeal. The lack of robust automated edit-quality metrics hinders reliable automation at scale. We present an automated, modular pipeline that mines high-fidelity triplets across domains, resolutions, instruction complexities, and styles. Built on public generative models and running without human intervention, our system uses a task-tuned Gemini validator to score instruction adherence and aesthetics directly, removing any need for segmentation or grounding models. Inversion and compositional bootstrapping enlarge the mined set by approximately 2.2x, enabling large-scale high-fidelity training data. By automating the most repetitive annotation steps, the approach allows a new scale of training without human labeling effort. To democratize research in this resource-intensive area, we release NHR-Edit: an open dataset of 358k high-quality triplets. In the largest cross-dataset evaluation, it surpasses all public alternatives. We also release Bagel-NHR-Edit, an open-source fine-tuned Bagel model, which achieves state-of-the-art metrics in our experiments.

https://huggingface.co/discussions/paper/687dfaee2e8db0930be6f194