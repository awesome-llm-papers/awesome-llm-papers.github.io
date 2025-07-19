---
layout: publication
title: Enabling Factorized Piano Music Modeling And Generation With The MAESTRO Dataset
authors: Hawthorne et al.
conference: Arxiv
year: 2018
bibkey: hawthorne2018enabling
citations: 144
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1810.12247'}]
tags: [Datasets]
---
Generating musical audio directly with neural networks is notoriously
difficult because it requires coherently modeling structure at many different
timescales. Fortunately, most music is also highly structured and can be
represented as discrete note events played on musical instruments. Herein, we
show that by using notes as an intermediate representation, we can train a
suite of models capable of transcribing, composing, and synthesizing audio
waveforms with coherent musical structure on timescales spanning six orders of
magnitude (~0.1 ms to ~100 s), a process we call Wave2Midi2Wave. This large
advance in the state of the art is enabled by our release of the new MAESTRO
(MIDI and Audio Edited for Synchronous TRacks and Organization) dataset,
composed of over 172 hours of virtuosic piano performances captured with fine
alignment (~3 ms) between note labels and audio waveforms. The networks and the
dataset together present a promising approach toward creating new expressive
and interpretable neural models of music.