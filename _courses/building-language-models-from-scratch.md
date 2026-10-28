---
title: "Building Language Models from Scratch (UdS)"
collection: courses
published: true
type: "Software Project"
permalink: /courses/building-language-models-from-scratch/
semester: "Winter 2026/27"
level: "Master"
venue: "Saarland University"
date: 2026-10-28
location: "Saarbrücken, Germany"
sitemap: true
share: false
---

## Course Description

Language models are a cornerstone of modern general-purpose AI systems.
Understanding how they are built and trained is essential for scientists and
engineers working with these systems. This software project is designed to
develop that understanding by building a language model from scratch.

You will implement a complete pipeline, including core model components such as
multi-head attention, training-data preparation and loading, and model training
and evaluation. You will investigate how data, architecture, optimizer,
and hyper-parameters choices affect
model quality, training cost, and inference efficiency, and use your
findings to guide further improvements.
You will then choose a task or application
and use supervised fine-tuning (SFT) to adapt your own pretrained model to it.

Specifically, you will work in a group of **3–4 students** to build, pretrain,
fine-tune, and evaluate a language model with
**fewer than 100 million parameters except for embeddings**,
using **PyTorch**. Lightning Fabric is also allowed. Your final model, experiments,
and analysis will form the basis of a **group report and presentation**.

## Prerequisites and Information

You should be comfortable programming in Python and PyTorch, including writing
and debugging a training loop. We assume basic knowledge of neural networks,
gradient-based optimization, and Transformers.

- **Instructor:** [Yupei Du](https://ypdu.github.io/) (yudo [at] lst [dot] uni-saarland [dot] de)
- **Course interest:** [Google Form](https://forms.gle/YQFJE9nMPfpY8UZt5)

- We will not have classes or lectures before the group presentations.
Instead, each group will have a **30-min weekly meeting with the instructor** to discuss progress.
Both online and in-person meetings are possible.

## The Project

Each group will establish a working baseline, investigate its design and training,
and adapt it to a self-selected task through SFT. The project follows the same
model from random initialization through pretraining and post-training. Groups
may pursue different questions and applications; there are no assigned tracks.

### 1. Build a modern Transformer baseline (~3 weeks)

The starting architecture is a small decoder-only Transformer with:

- causal multi-head attention;
- pre-normalization using RMSNorm;
- rotary position embeddings (RoPE);
- a SwiGLU feed-forward network.

A reference implementation is available in
[Raschka's GPT-to-Llama-2 walkthrough](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch05/07_gpt_to_llama/converting-gpt-to-llama2.ipynb).
All experimental language models must have
**fewer than 100 million total parameters excluding embeddings**,
with shared parameters count once.

You will develop and maintain a clear **PyTorch** implementation
of the model components and training loop.
Choose a suitable depth, width, context length, and training configuration.
Standard PyTorch operations, optimizers, tokenizer libraries, and dataset tools
may be used. Lightning Fabric is also allowed.

You should also choose a pretraining corpus appropriate for your model.
Some possible sources include:

- [TinyStories](https://huggingface.co/datasets/roneneldan/TinyStories): synthetic
  short stories with simple vocabulary, useful for initial experiments with small models.
- [FineWeb-Edu](https://huggingface.co/datasets/HuggingFaceFW/fineweb-edu): English
  web text filtered for educational quality. Select a subset that fits your resources.

You may use other suitable corpora or explore mixtures.
Document the sources, preprocessing, tokenization, and sampling decisions.


### 2. Evaluation and iteration (~4 weeks)

After building a working baseline, you will need to properly evaluate it.
Evaluation might seem straightforward,
but it is a very important part of modern machine learning research,
and can be surprisingly tricky.

You should develop a comprehensive evaluation suite,
including different datasets and tasks,
that measures model quality, training cost, and inference efficiency.
It is also often useful to just look at the model's outputs and analyze its errors.
Some useful metrics are:

| Aspect | Measurements |
| --- | --- |
| Quality | Held-out language-model loss, task-specific results, and error analysis |
| Training | token throughput, peak GPU memory, and validation loss over training time |
| Inference | latency and throughput for both prefilling and decoding|

You will then decide what bottlenecks your model has and how to address them.
You should also find the best hyper-parameters, where
a useful reference is the
[Deep Learning Tuning Playbook](https://github.com/google-research/tuning_playbook).
Make informed choices.
Record the reasoning and supporting results behind your design choices,


### 3. Adapt your model to a task through SFT (~3 weeks)

Choose a task or application and use **supervised fine-tuning (SFT) on your own
pretrained model** to improve its performance on that task.
For example, you might build a nano chatbot, a summarizer,
or small code generator.

Similar to pretraining, you will need to choose a suitable dataset
to train and evaluate your model.
You should also consider making changes according to the results.

### 4. Report and present your findings

You will then prepare a **group presentation** for your classmates,
detailing your baseline, experiments, and findings.
Each presentation should take **20 minutes**, followed by **10 minutes of discussion**.
The presentation will take place on **January 21, 2027**.

You will also need to prepare a **group report** in NeurIPS format,
with up to ten pages excluding references and appendices.
You should include a clear description of your baseline, experiments, and findings,
as well as a contribution statement for each group member.
The deadline for the report is **the end of March 2027**.

## Semester Plan

| Dates | Task |
| --- | --- |
| October 29–November 18, 2026 | Build and pretrain a modern Transformer baseline |
| November 19–December 16, 2026 | Evaluate and improve model quality, training cost, and inference efficiency |
| December 17, 2026–January 20, 2027 | Adapt your pretrained model to a self-selected task through SFT |
| January 21, 2027 | Group presentations |
| End of March 2027 | Submit the final report and project materials |

## Evaluation

```
Project work: 60%
Presentation: 10%
Final report: 30%
```

## AI Policy

AI assistance is allowed. You remain responsible for the correctness of your work.
You might be asked to explain your experiments and results in detail,
and you might also be asked to explain the specific mechanisms of your model and training loop.
All usage should be documented in the report.

## Starting Resources

- [Stanford CS336: Language Modeling from Scratch](https://cs336.stanford.edu/)
  — lectures and assignments on model implementation, training, data, and evaluation.
- [Deep Learning Tuning Playbook](https://github.com/google-research/tuning_playbook)
  — practical guidance on experimental design, training diagnostics, and systematic
  tuning. Focus on the experimental methodology; validate specific recommendations
  for your model, data, and compute budget.
- [Raschka: Converting GPT to Llama 2](https://github.com/rasbt/LLMs-from-scratch/blob/main/ch05/07_gpt_to_llama/converting-gpt-to-llama2.ipynb)
  — a step-by-step explanation of RMSNorm, RoPE, and SwiGLU. The notebook also
  demonstrates loading pretrained weights; this project uses random initialization.
- [Qwen3 Technical Report](https://arxiv.org/abs/2505.09388)
  — an example of the architecture and training choices in a modern model family.
- [LFM2 Technical Report](https://arxiv.org/abs/2511.23404)
  — architecture design and evaluation with quality, latency, and memory in mind.
- [TinyStories paper](https://arxiv.org/abs/2305.07759)
  — small-scale language modeling with synthetic stories.
- [The FineWeb Datasets: Decanting the Web for the Finest Text Data at Scale](https://arxiv.org/abs/2406.17557)
  — data curation, filtering, and deduplication for FineWeb and FineWeb-Edu.
- [PyTorch Profiler](https://docs.pytorch.org/tutorials/recipes/recipes/profiler_recipe.html)
  — tools for understanding training time and memory use.
