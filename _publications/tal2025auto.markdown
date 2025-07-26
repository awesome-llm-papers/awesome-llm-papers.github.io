---
layout: publication
title: 'Auto-regressive Vs Flow-matching: A Comparative Study Of Modeling Paradigms
  For Text-to-music Generation'
authors: Or Tal, Felix Kreuk, Yossi Adi
conference: No Venue
year: 2025
bibkey: tal2025auto
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2506.08570'}]
tags: ["Model Architecture"]
short_authors: Or Tal, Felix Kreuk, Yossi Adi
---
Recent progress in text-to-music generation has enabled models to synthesize high-quality musical segments, full compositions, and even respond to fine-grained control signals, e.g. chord progressions. State-of-the-art (SOTA) systems differ significantly across many dimensions, such as training datasets, modeling paradigms, and architectural choices. This diversity complicates efforts to evaluate models fairly and pinpoint which design choices most influence performance. While factors like data and architecture are important, in this study we focus exclusively on the modeling paradigm. We conduct a systematic empirical analysis to isolate its effects, offering insights into associated trade-offs and emergent behaviors that can guide future text-to-music generation systems. Specifically, we compare the two arguably most common modeling paradigms: Auto-Regressive decoding and Conditional Flow-Matching. We conduct a controlled comparison by training all models from scratch using identical datasets, training configurations, and similar backbone architectures. Performance is evaluated across multiple axes, including generation quality, robustness to inference configurations, scalability, adherence to both textual and temporally aligned conditioning, and editing capabilities in the form of audio inpainting. This comparative study sheds light on distinct strengths and limitations of each paradigm, providing actionable insights that can inform future architectural and training decisions in the evolving landscape of text-to-music generation. Audio sampled examples are available at: https://huggingface.co/spaces/ortal1602/ARvsFM

https://huggingface.co/discussions/paper/684982b5d546b83e67deb344