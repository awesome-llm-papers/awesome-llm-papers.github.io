---
layout: publication
title: 'Melnet: A Generative Model For Audio In The Frequency Domain'
authors: Sean Vasquez, Mike Lewis
conference: Arxiv
year: 2019
bibkey: vasquez2019melnet
citations: 118
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1906.01083'}]
tags: ["Model Architecture"]
short_authors: Sean Vasquez, Mike Lewis
---
Capturing high-level structure in audio waveforms is challenging because a
single second of audio spans tens of thousands of timesteps. While long-range
dependencies are difficult to model directly in the time domain, we show that
they can be more tractably modelled in two-dimensional time-frequency
representations such as spectrograms. By leveraging this representational
advantage, in conjunction with a highly expressive probabilistic model and a
multiscale generation procedure, we design a model capable of generating
high-fidelity audio samples which capture structure at timescales that
time-domain models have yet to achieve. We apply our model to a variety of
audio generation tasks, including unconditional speech generation, music
generation, and text-to-speech synthesis---showing improvements over previous
approaches in both density estimates and human judgments.