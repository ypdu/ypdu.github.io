---
title: "Diffusion Language Models (UdS, Summer 26)"
collection: courses
type: "Seminar"
permalink: /courses/diffusion-language-models-seminar-summer-26/
semester: "Summer 26"
level: "Master"
venue: "Saarland University"
date: 2026-04-10
location: "Saarbrücken, Germany"
---

## Course Description

Autoregressive language models generate text one token at a time from left to right,
which can limit their efficiency and flexibility.
Diffusion language models offer an alternative paradigm:
they define a generative process by learning to reverse a corruption process
that gradually transforms data into noise,
enabling parallel and non-sequential generation.
This seminar explores recent work on diffusion language models,
covering modeling objectives, architectures, decoding algorithms, scaling behavior,
and applications to reasoning and planning.

## Prerequisites

This course assumes solid background in NLP and ML. 
The papers we will discuss are often highly technical; 
while you are not expected to understand every detail of every paper, 
understanding the main ideas and being able to discuss them critically is essential.

## Information

- **Instructor:** [Yupei Du](https://ypdu.github.io/) (yudo [at] lst [dot] uni-saarland [dot] de)
- **Time/Location:** Fri 08:30 - 10:00; Gebäude C7 3 - Seminarraum 1.14

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
| 1  | 10-04-2026 | Introduction | [Slides](https://docs.google.com/presentation/d/1UkCul2SEr5HIx8fKwRhMwadvTizXD-_SdNZSTkKkM_4/edit?usp=sharing) | Yupei  |
| -  | 17-04-2026 | No class     |         |        |
| 2  | 24-04-2026 | Discrete diffusion | [Structured Denoising Diffusion Models in Discrete State-Spaces](https://arxiv.org/abs/2107.03006) | Fanyi Meng |
| -  | 01-05-2026 | No class     |         |        |
| 3  | 08-05-2026 | Masked diffusion language models | [Simple and Effective Masked Diffusion Language Models](https://arxiv.org/abs/2406.07524) | Jia Liu |
| 4  | 15-05-2026 | Rethinking masked diffusion |         | Anthony John Dsouza |
| -  | 22-05-2026 | Guest lecture: Diffusion LLMs can think EoS-by-EoS |         | Sarah Breckner |
| 5  | 29-05-2026 | More flexible training objectives |         | Pranav Prakash Kushare |
| 6  | 05-06-2026 | Scaling diffusion language models |         | Shane John Paul Newton |
| 7  | 12-06-2026 | Diffusion for reasoning and planning |         | Juangui Xu |
| 8  | 19-06-2026 | Analysis of masked diffusion | [Revealing the Attention Floating Mechanism in Masked Diffusion Models](https://arxiv.org/abs/2601.07894) | Tianchi Gu |
| 9  | 26-06-2026 | Is the arbitrary token ordering a bug? |         | Zichao Wei |
| 10 | 03-07-2026 | TBD          |         |        |
| 11 | 10-07-2026 | TBD          |         |        |
| 12 | 17-07-2026 | TBD          |         |        |

## Suggested Readings

The topics below are listed in sequence rather than tied to fixed weeks.

### 1. Continuous diffusion foundations

- Denoising Diffusion Probabilistic Models 
- Score-Based Generative Modeling through SDEs 

### 2. Discrete diffusion 

- Structured Denoising Diffusion Models in Discrete State-Spaces 
- A Continuous Time Framework for Discrete Denoising Models 

### 3. Masked diffusion language models

- Simple and Effective Masked Diffusion Language Models 
- Scaling up Masked Diffusion Models on Text 

### 4. More flexible training objectives

- Discrete Diffusion Modeling by Estimating the Ratios of the Data Distribution 
- A Reparameterized Discrete Diffusion Model for Text Generation 

### 5. Rethinking masked diffusion

- Masked Diffusion Models are Secretly Time-Agnostic 
- Your Absorbing Discrete Diffusion Secretly Models the Conditional Distributions of Clean Data 

### 6. Scaling diffusion language models

- Diffusion Language Models are Super Data Learners 
- Scaling Behavior of Discrete Diffusion Language Models 

### 7. Is the arbitrary token ordering a bug?

- Train for the Worst, Plan for the Best: Understanding Token Ordering in Masked Diffusions 
- Think While You Generate: Discrete Diffusion with Planned Denoising

### 8. Autoregression and diffusion

- Block Diffusion: Interpolating Between Autoregressive and Diffusion Language Models 
- AR-Diffusion: Auto-Regressive Diffusion Model for Text Generation 

### 9. Diffusion for reasoning and planning

- Beyond Autoregression: Discrete Diffusion for Complex Reasoning and Planning 
- Diffusion of Thoughts: Chain-of-Thought in DLMs 

### 10. Analysis of masked diffusion

- Generalized Interpolating Discrete Diffusion 
- Why Masking Diffusion Works: Condition on the Jump Schedule for Improved Discrete Diffusion 

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
with the subject line "Diffusion seminar term paper submission: [Your Name]".

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
