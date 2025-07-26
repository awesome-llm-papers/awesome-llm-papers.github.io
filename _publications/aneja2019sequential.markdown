---
layout: publication
title: Sequential Latent Spaces For Modeling The Intention During Diverse Image Captioning
authors: Jyoti Aneja, Harsh Agrawal, Dhruv Batra, Alexander Schwing
conference: 2019 IEEE/CVF International Conference on Computer Vision (ICCV)
year: 2019
bibkey: aneja2019sequential
citations: 60
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1908.08529'}]
tags: ["ICCV"]
short_authors: Aneja et al.
---
Diverse and accurate vision+language modeling is an important goal to retain
creative freedom and maintain user engagement. However, adequately capturing
the intricacies of diversity in language models is challenging. Recent works
commonly resort to latent variable models augmented with more or less
supervision from object detectors or part-of-speech tags. Common to all those
methods is the fact that the latent variable either only initializes the
sentence generation process or is identical across the steps of generation.
Both methods offer no fine-grained control. To address this concern, we propose
Seq-CVAE which learns a latent space for every word position. We encourage this
temporal latent space to capture the 'intention' about how to complete the
sentence by mimicking a representation which summarizes the future. We
illustrate the efficacy of the proposed approach to anticipate the sentence
continuation on the challenging MSCOCO dataset, significantly improving
diversity metrics compared to baselines while performing on par w.r.t sentence
quality.