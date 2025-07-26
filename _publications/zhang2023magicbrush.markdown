---
layout: publication
title: 'Magicbrush: A Manually Annotated Dataset For Instruction-guided Image Editing'
authors: Kai Zhang, Lingbo Mo, Wenhu Chen, Huan Sun, Yu Su
conference: No Venue
year: 2023
bibkey: zhang2023magicbrush
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/hf2306.10012'}]
tags: ["Datasets"]
short_authors: Zhang et al.
---
Text-guided image editing is widely needed in daily life, ranging from personal use to professional applications such as Photoshop. However, existing methods are either zero-shot or trained on an automatically synthesized dataset, which contains a high volume of noise. Thus, they still require lots of manual tuning to produce desirable outcomes in practice. To address this issue, we introduce MagicBrush (https://osu-nlp-group.github.io/MagicBrush/), the first large-scale, manually annotated dataset for instruction-guided real image editing that covers diverse scenarios: single-turn, multi-turn, mask-provided, and mask-free editing. MagicBrush comprises over 10K manually annotated triples (source image, instruction, target image), which supports trainining large-scale text-guided image editing models. We fine-tune InstructPix2Pix on MagicBrush and show that the new model can produce much better images according to human evaluation. We further conduct extensive experiments to evaluate current image editing baselines from multiple dimensions including quantitative, qualitative, and human evaluations. The results reveal the challenging nature of our dataset and the gap between current baselines and real-world editing needs.

https://huggingface.co/discussions/paper/648faa9819234cd09c480d76