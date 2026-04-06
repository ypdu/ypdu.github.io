---
title: "LLM Complex Reasoning (UdS, Summer 26)"
collection: courses
type: "Seminar"
permalink: /courses/llm-complex-reasoning-seminar-summer-26/
semester: "Summer 26"
level: "Master"
venue: "Saarland University"
date: 2026-04-10
location: "Saarbrücken, Germany"
---

## Course Description

What does it take for language models to reason reliably about complex, multi-step problems?
This seminar investigates this question through three interconnected lenses.
First, _can models reason without producing explicit reasoning traces?_
We examine latent and continuous chain-of-thought methods, looped and recurrent transformers,
and diffusion-based approaches that internalize reasoning into hidden computation.
Second, _do current architectures impose fundamental limits on reasoning?_
We study how architectural choices — from attention and state-space models
to associative memory and linear recurrences — shape
what models can and cannot learn to compose and generalize.
Third, _how can models adapt their computation to the difficulty of a problem?_
We explore test-time training, long-context reasoning,
and predictive world models as mechanisms for flexible, problem-dependent computation.

## Prerequisites

This course assumes solid background in NLP and ML. 
The papers we will discuss are often highly technical; 
while you are not expected to understand every detail of every paper, 
understanding the main ideas and being able to discuss them critically is essential.

## Information

- **Instructor:** [Yupei Du](https://yupei.nl/) (yudo [at] lst [dot] uni-saarland [dot] de)
- **Time/Location:** Fri 12:15 - 13:45; Gebäude C7 3 - Seminarraum 1.14

## Format/Requirements

Each week, we will meet to discuss the assigned topic. 
Each session will focus on one or two recent papers relevant to the topic of the week,
led by one or two students who will present the paper(s) for approximately 45-60 minutes,
followed by a group discussion of another 30-45 minutes.

### For presenters

Discussion is not limited to after presentations only,
and you should regularly pause to ask if there are any questions or comments,
and encourage the audience to share their thoughts.
Some suggested readings are offered for each topic;
however, **these are by no means exhaustive, and
you are very welcome to propose readings that you are interested in to present**,
as long as they are related to the topic of the seminar.
Please email me such suggestions at least **one week before the relevant session**,
so that I can review and approve them in time.

It is fine if you do not understand every detail of the paper you’ll present,
and you are not expected to cover all of them in your presentation.
Rather, our focus will be building understanding about
the main problems addressed, the background, why they are important,
why the proposed solutions work (or don’t work),
and possible engineering tricks used by the authors to improve the results.
You are also encouraged to critically evaluate the paper, discussing
whether the claims are well-supported by the evidence, its limitations,
potential future directions, and the broader implications of the work.
**Make sure to make your presentation accessible to the audience,
who may not be familiar with all the technical details of the paper**,
and do not hesitate to repeat or rephrase things if necessary.
After presentations, please send me your slides and other materials for archiving purposes.

### For audience

All students are expected to ask questions and actively engage in the discussion.
Each session you will be graded based on your participation, including:
- 0 (not engaged)
- 1 (asked questions or made comments)
- 2 (asked high-quality questions or made thoughtful comments)

## Syllabus

| #  | Date       | Topic        | Reading | Leader |
| -- | ---------- | ------------ | ------- | ------ |
| 1  | 10-04-2026 | Introduction |         | Yupei  |
| 2  | 17-04-2026 | TBD          |         |        |
| 3  | 24-04-2026 | TBD          |         |        |
| -  | 01-05-2026 | No class     |         |        |
| 4  | 08-05-2026 | TBD          |         |        |
| 5  | 15-05-2026 | TBD          |         |        |
| 6  | 22-05-2026 | TBD          |         |        |
| 7  | 29-05-2026 | TBD          |         |        |
| 8  | 05-06-2026 | TBD          |         |        |
| 9  | 12-06-2026 | TBD          |         |        |
| 10 | 19-06-2026 | TBD          |         |        |
| 11 | 26-06-2026 | TBD          |         |        |
| 12 | 03-07-2026 | TBD          |         |        |
| 13 | 10-07-2026 | TBD          |         |        |
| 14 | 17-07-2026 | TBD          |         |        |

## Suggested Readings

The topics below are listed in sequence rather than tied to fixed weeks.

### 1. Continuous / Latent Chain-of-Thought

- Training Large Language Models to Reason in a Continuous Latent Space 
- Soft Thinking: Unlocking the Reasoning Potential of LLMs in Continuous Concept Space

### 2. Looped Transformers as a Reasoning Bias

- Reasoning with Latent Thoughts: On the Power of Looped Transformers
- Looped Transformers for Length Generalization

### 3. Recurrent Depth and Latent Reasoning

- Scaling up Test-Time Compute with Latent Reasoning: A Recurrent Depth Approach
- LoopFormer: Elastic-Depth Looped Transformers for Latent Reasoning via Shortcut Modulation

### 4. Diffusion and Non-Autoregressive Reasoning

- Beyond Autoregression: Discrete Diffusion for Complex Reasoning and Planning
- d1: Scaling Reasoning in Diffusion Large Language Models via Reinforcement Learning

### 5. Linear Transformers as Memory Updates

- Parallelizing Linear Transformers with the Delta Rule over Sequence Length
- Gated Delta Networks: Improving Mamba2 with Delta Rule

### 6. Mamba

- Linear-Time Sequence Modeling with Selective State Spaces
- Transformers are SSMs: Generalized Models and Efficient Algorithms Through Structured State Space Duality
- Improved Sequence Modeling using State Space Principles

### 7. Associative Memory Perspectives on Transformers

- Understanding Transformer from the Perspective of Associative Memory
- Linear Transformers Are Secretly Fast Weight Programmers

### 8. Generalization and Compositional Reasoning

- Faith and Fate: Limits of Transformers on Compositionality
- Grokked Transformers are Implicit Reasoners: A Mechanistic Journey to the Edge of Generalization

### 9. Test-Time Training

- Learning to (Learn at Test Time): RNNs with Expressive Hidden States
- End-to-End Test-Time Training for Long Context

### 10. Multi-Token Prediction

- Better & Faster Large Language Models via Multi-token Prediction
- Beyond Multi-Token Prediction: Pretraining LLMs with Future Summaries

### 11. Context Learning

- Recursive Language Models
- CL-bench: A Benchmark for Context Learning

### 12. Predictive World Models

- V-JEPA 2: Self-Supervised Video Models Enable Understanding, Prediction and Planning
- LeWorldModel: Stable End-to-End Joint-Embedding Predictive Architecture from Pixels

## Term paper (for the 7 CP version)

Students taking the course for 7 credits will be expected to write a term paper.
The term paper follows one of the following two formats:
- A survey paper on a topic relevant to the course; or
- A small yet well-executed independent project.

For the survey paper, you should pick a topic that you are interested in,
identify a few key problems,
and choose at least three important papers that address each problem.
Similar to the presentations, you should not only summarize the papers,
but also clearly frame and motivate the key problems,
as well as the proposed solutions from each paper,
analyze their strengths and weaknesses,
and discuss potential future extensions.

For the independent project,
you should identify a research question that is relevant and interesting to you,
clearly frame and motivate the problem, discuss past work,
and propose a set of experiments to address the problem.
This project can take different forms:
for example, it can be reproducing and extending an existing work,
systematically comparing different methods on a specific problem,
or proposing a novel method to address an existing problem.
Here is a guide on [how to write an OK research paper](https://www.youtube.com/watch?v=qNlwVGxkG7Q).

### Format

Up to 10 pages (excluding references and appendix) texts in
[NeurIPS format](https://neurips.cc/Conferences/2025/CallForPapers).
The submission should be a PDF file.
There is no strict minimum length, or which software you should use to write the paper.
However, please make sure that the formatting is clear, consistent, and self-contained.
I personally recommend using [Typst](https://typst.app/) or LaTeX for writing.

### Submission deadline

Due: end of August 2026. Send me an email with the PDF attached,
with the subject line "Complex reasoning seminar term paper submission: [Your Name]".

### LLM use policy

This course does not place formal restrictions on the use of LLMs or other AI tools for learning.
However, **any use of AI tools must be clearly documented**.
Moreover, **you are fully responsible for the content of your paper**,
regardless of whether it was produced by you or with the help of AI.
For example, if your work contains
poorly executed experiments, logical flaws, plagiarism, or fabricated citations or content,
no matter the source, your grade will be affected.
Therefore, please use AI tools thoughtfully, responsibly, and with a critical mindset.

## Evaluation

*Important: study programs may differ in which versions of the class you can take.
Please check with your study program coordinator if in doubt.*

### For students taking the seminar for 4 credits:

```
Presentation: 60%
Participation: 40%
```

### For students taking the seminar for 7 credits:

```
Presentation: 30%
Participation: 20%
Term paper: 50%
```

## Contact

For questions about the course, please contact Yupei via email.
