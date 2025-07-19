---
layout: publication
title: Towards Human-like Spoken Dialogue Generation Between AI Agents From Written
  Dialogue
authors: Mitsui Kentaro, Hono Yukiya, Sawada Kei
conference: Speech Communication
year: 2023
bibkey: mitsui2023towards
citations: 75
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2310.01088'}]
tags: [INTERSPEECH, Agentic, Reinforcement Learning, Evaluation]
---
The advent of large language models (LLMs) has made it possible to generate
natural written dialogues between two agents. However, generating human-like
spoken dialogues from these written dialogues remains challenging. Spoken
dialogues have several unique characteristics: they frequently include
backchannels and laughter, and the smoothness of turn-taking significantly
influences the fluidity of conversation. This study proposes CHATS - CHatty
Agents Text-to-Speech - a discrete token-based system designed to generate
spoken dialogues based on written dialogues. Our system can generate speech for
both the speaker side and the listener side simultaneously, using only the
transcription from the speaker side, which eliminates the need for
transcriptions of backchannels or laughter. Moreover, CHATS facilitates natural
turn-taking; it determines the appropriate duration of silence after each
utterance in the absence of overlap, and it initiates the generation of
overlapping speech based on the phoneme sequence of the next utterance in case
of overlap. Experimental evaluations indicate that CHATS outperforms the
text-to-speech baseline, producing spoken dialogues that are more interactive
and fluid while retaining clarity and intelligibility.