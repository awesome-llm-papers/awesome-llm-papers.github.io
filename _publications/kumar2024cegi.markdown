---
layout: publication
title: 'CEGI: Measuring The Trade-off Between Efficiency And Carbon Emissions For
  Slms And Vlms'
authors: Kumar et al.
conference: Energy Policy
year: 2024
bibkey: kumar2024cegi
citations: 153
additional_links: [{name: Paper, url: 'https://arxiv.org/abs/2412.02602'}]
tags: [RAG, Training Techniques, Model Architecture, Efficiency And Optimization,
  Fine Tuning, Quantization]
---
This paper analyzes the performance of Small Language Models (SLMs) and
Vision Language Models (VLMs) and evaluates the trade-off between model
performance and carbon emissions across 4 essential tasks: Image Captioning,
Visual Question Answering (VQA), Dialogue Summarization and Text-to-SQL
conversion. Various SLMs and VLMs belonging to the Qwen and LLaMA architecture
family are chosen and variants based on model size in terms of the number of
parameters, quantization level and fine-tuning parameters are evaluated. The
model variant's performance and carbon emissions are calculated. To quantify
the trade-off between model performance and carbon emissions, we introduce a
novel metric called CEGI (Carbon Efficient Gain Index). This metric represents
the carbon emission per unit percentage gain per million trainable parameters .
This metric provides a normalized measure to compare model's efficiency in
terms of performance improvement relative to their environmental cost. The
experiment's outcome demonstrates that fine-tuning SLMs and VLMs can achieve
performance levels comparable to Large Language Models (LLMs) while producing
significantly less carbon emissions. Our findings suggest that the marginal
gains in accuracy from larger models do not justify the substantial increase in
carbon emissions. Leveraging lower-bit quantization levels, the proposed metric
further enhances energy efficiency without compromising performance. This study
highlights balancing high performance and environmental sustainability. It
offers a valuable metric for selecting models suitable for
environmentally-friendly AI development.