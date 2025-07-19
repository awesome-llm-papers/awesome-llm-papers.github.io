---
layout: publication
title: 'Augmenting Librispeech With French Translations: A Multimodal Corpus For Direct
  Speech Translation Evaluation'
authors: Kocabiyikoglu Ali Can, Besacier Laurent, Kraif Olivier
conference: Arxiv
year: 2018
bibkey: kocabiyikoglu2018augmenting
citations: 74
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/1802.03142'}]
tags: [Datasets, Training Techniques, Evaluation, Reinforcement Learning, Multimodal
    Models, SLT]
---
Recent works in spoken language translation (SLT) have attempted to build
end-to-end speech-to-text translation without using source language
transcription during learning or decoding. However, while large quantities of
parallel texts (such as Europarl, OpenSubtitles) are available for training
machine translation systems, there are no large (100h) and open source parallel
corpora that include speech in a source language aligned to text in a target
language. This paper tries to fill this gap by augmenting an existing
(monolingual) corpus: LibriSpeech. This corpus, used for automatic speech
recognition, is derived from read audiobooks from the LibriVox project, and has
been carefully segmented and aligned. After gathering French e-books
corresponding to the English audio-books from LibriSpeech, we align speech
segments at the sentence level with their respective translations and obtain
236h of usable parallel data. This paper presents the details of the processing
as well as a manual evaluation conducted on a small subset of the corpus. This
evaluation shows that the automatic alignments scores are reasonably correlated
with the human judgments of the bilingual alignment quality. We believe that
this corpus (which is made available online) is useful for replicable
experiments in direct speech translation or more general spoken language
translation experiments.