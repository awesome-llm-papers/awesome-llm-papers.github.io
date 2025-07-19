---
layout: publication
title: 'Molreflect: Towards In-context Fine-grained Alignments Between Molecules And
  Texts'
authors: Li et al.
conference: 2013 IEEE International Conference on Computer Vision
year: 2024
bibkey: li2024molreflect
citations: 137
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2411.14721'}]
tags: [RAG, Tools, Datasets, ICCV]
---
Molecule discovery is a pivotal research field, impacting everything from the
medicines we take to the materials we use. Recently, Large Language Models
(LLMs) have been widely adopted in molecule understanding and generation, yet
the alignments between molecules and their corresponding captions remain a
significant challenge. Previous endeavours often treat the molecule as a
general SMILES string or molecular graph, neglecting the fine-grained
alignments between the molecular sub-structures and the descriptive textual
phrases, which are crucial for accurate and explainable predictions. In this
case, we introduce MolReFlect, a novel teacher-student framework designed to
contextually perform the molecule-caption alignments in a fine-grained way. Our
approach initially leverages a larger teacher LLM to label the detailed
alignments by directly extracting critical phrases from molecule captions or
SMILES strings and implying them to corresponding sub-structures or
characteristics. To refine these alignments, we propose In-Context Selective
Reflection, which retrieves previous extraction results as context examples for
teacher LLM to reflect and lets a smaller student LLM select from in-context
reflection and previous extraction results. Finally, we enhance the learning
process of the student LLM through Chain-of-Thought In-Context Molecule Tuning,
integrating the fine-grained alignments and the reasoning processes within the
Chain-of-Thought format. Our experimental results demonstrate that MolReFlect
enables LLMs like Mistral-7B to significantly outperform the previous
baselines, achieving SOTA performance on the ChEBI-20 dataset. This advancement
not only enhances the generative capabilities of LLMs in the molecule-caption
translation task, but also contributes to a more explainable framework.