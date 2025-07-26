---
layout: publication
title: Leveraging Abstract Meaning Representation For Knowledge Base Question Answering
authors: Pavan Kapanipathi, Ibrahim Abdelaziz, Srinivas Ravishankar, Salim Roukos,
  Alexander Gray, Ramon Astudillo, Maria Chang, Cristina Cornelio, Saswati Dana, Achille
  Fokoue, Dinesh Garg, Alfio Gliozzo, Sairam Gurajada, Hima Karanam, Naweed Khan,
  Dinesh Khandelwal, Young-suk Lee, Yunyao Li, Francois Luus, Ndivhuwo Makondo, Nandana
  Mihindukulasooriya, Tahira Naseem, Sumit Neelam, Lucian Popa, Revanth Reddy, Ryan
  Riegel, Gaetano Rossiello, Udit Sharma, G P Shrivatsa Bhargav, Mo Yu
conference: 'Findings of the Association for Computational Linguistics: ACL-IJCNLP
  2021'
year: 2021
bibkey: kapanipathi2020leveraging
citations: 74
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2012.01707'}]
tags: []
short_authors: Kapanipathi et al.
---
Knowledge base question answering (KBQA)is an important task in Natural
Language Processing. Existing approaches face significant challenges including
complex question understanding, necessity for reasoning, and lack of large
end-to-end training datasets. In this work, we propose Neuro-Symbolic Question
Answering (NSQA), a modular KBQA system, that leverages (1) Abstract Meaning
Representation (AMR) parses for task-independent question understanding; (2) a
simple yet effective graph transformation approach to convert AMR parses into
candidate logical queries that are aligned to the KB; (3) a pipeline-based
approach which integrates multiple, reusable modules that are trained
specifically for their individual tasks (semantic parser, entity
andrelationship linkers, and neuro-symbolic reasoner) and do not require
end-to-end training data. NSQA achieves state-of-the-art performance on two
prominent KBQA datasets based on DBpedia (QALD-9 and LC-QuAD1.0). Furthermore,
our analysis emphasizes that AMR is a powerful tool for KBQA systems.