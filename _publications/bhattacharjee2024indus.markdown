---
layout: publication
title: 'INDUS: Effective And Efficient Language Models For Scientific Applications'
authors: Bishwaranjan Bhattacharjee, Aashka Trivedi, Masayasu Muraoka, Muthukumaran
  Ramasubramanian, Takuma Udagawa, Iksha Gurung, Rong Zhang, Bharath Dandala, Rahul
  Ramachandran, Manil Maskey, Kayleen Bugbee, Mike Little, Elizabeth Fancher, Lauren
  Sanders, Sylvain Costes, Sergi Blanco-cuaresma, Kelly Lockhart, Thomas Allen, Felix
  Grazes, Megan Ansdel, Alberto Accomazzi, Yousef El-kurdi, Davis Wertheimer, Birgit
  Pfitzmann, Cesar Berrospi Ramis, Michele Dolfi, Rafael Teixeira de Lima, Panos Vegenas,
  S. Karthik Mukkavilli, Peter Staar, Sanaz Vahidinia, Ryan Mcgranaghan, Armin Mehrabian,
  Tsendgar Lee
conference: No Venue
year: 2024
bibkey: bhattacharjee2024indus
additional_links: [{name: Code, url: 'https://huggingface.co/discussions/paper/664b68b8bfd9b93ba4ac00c3'},
  {name: Paper, url: 'https://arxiv.org/abs/hf2405.10725'}]
tags: ["Applications", "Datasets", "Efficiency"]
short_authors: Bhattacharjee et al.
---
Large language models (LLMs) trained on general domain corpora showed remarkable results on natural language processing (NLP) tasks. However, previous research demonstrated LLMs trained using domain-focused corpora perform better on specialized tasks. Inspired by this pivotal insight, we developed INDUS, a comprehensive suite of LLMs tailored for the Earth science, biology, physics, heliophysics, planetary sciences and astrophysics domains and trained using curated scientific corpora drawn from diverse data sources. The suite of models include: (1) an encoder model trained using domain-specific vocabulary and corpora to address natural language understanding tasks, (2) a contrastive-learning-based general text embedding model trained using a diverse set of datasets drawn from multiple sources to address information retrieval tasks and (3) smaller versions of these models created using knowledge distillation techniques to address applications which have latency or resource constraints. We also created three new scientific benchmark datasets namely, CLIMATE-CHANGE-NER (entity-recognition), NASA-QA (extractive QA) and NASA-IR (IR) to accelerate research in these multi-disciplinary fields. Finally, we show that our models outperform both general-purpose encoders (RoBERTa) and existing domain-specific encoders (SciBERT) on these new tasks as well as existing benchmark tasks in the domains of interest.

https://huggingface.co/discussions/paper/664b68b8bfd9b93ba4ac00c3