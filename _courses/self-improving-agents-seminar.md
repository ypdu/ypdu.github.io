---
title: "Towards Self-Improving Agents (UdS, Winter 26/27)"
collection: courses
published: true
type: "Seminar"
permalink: /courses/self-improving-agents-seminar-winter-26/
semester: "Winter 26/27"
level: "Master"
venue: "Saarland University"
date: 2026-10-27
location: "Saarbrücken, Germany"
---

## Course Description

Can LLMs improve themselves? This seminar investigates how modern AI agents can learn to solve more tasks by spending more computation on reasoning, interacting with the world, learning from experience, and improving their own training procedures and tools.

We begin by examining how additional test-time computation can help models solve more problems, and what happens when models generate their own reward signals. We then study how agents can use experience more effectively by turning it into reusable memories and skills. Next, we explore whether LLMs can improve their own training by generating training tasks and curricula, and improve the systems they operate within by modifying their tools and agent harnesses. Finally, we examine how to evaluate self-improvement—and why establishing that an agent has genuinely improved is challenging—before turning to the risks that arise when self-improvement goes wrong.

## Prerequisites

This course assumes solid background in NLP and ML.
The papers we will discuss are often highly technical;
while you are not expected to understand every detail of every paper,
understanding the main ideas and being able to discuss them critically is essential.

## Information

- **Instructor:** [Yupei Du](https://ypdu.github.io/) (yudo [at] lst [dot] uni-saarland [dot] de)
- **Time/Location:** Tue 16:15 - 17:45; Gebäude C7 3 - Seminarraum 1.14

## Format/Requirements

Each week, we will meet to discuss the assigned topic.
Each session will focus on one main paper relevant to the topic of the week,
led by one or two students who will present the paper for approximately 45-60 minutes,
followed by a group discussion of another 30-45 minutes.

### For presenters

Discussion is not limited to after presentations only,
and you should regularly pause to ask if there are any questions or comments,
and encourage the audience to share their thoughts.
Some related research is listed for each topic;
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

<div class="seminar-schedule-scroll" markdown="1">

| # | Date | Topic | Reading | Leader |
| -- | -- | -- | -- | -- |
| 1 | 27-10-2026 | Introduction: reasoning, agents, and improvement | [Slides](https://docs.google.com/presentation/d/1NbojB0-V0Ef_5V2rAyjQIw5ZsWOLd6Shs9XudmM4Uis/edit) | Yupei |
| – | 03-11-2026 | No class | | |
| | | **Reasoning and inference-time computation** | | |
| 2 | 10-11-2026 | Repeated sampling and answer selection | [Large Language Monkeys: Scaling Inference Compute with Repeated Sampling](https://arxiv.org/abs/2407.21787) | Anthony John Dsouza |
| 3 | 17-11-2026 | What does RL actually learn? | [Does Reinforcement Learning Really Incentivize Reasoning Capacity in LLMs Beyond the Base Model?](https://arxiv.org/abs/2504.13837) | Juangui Xu |
| 4 | 24-11-2026 | Where does the reward come from? | [Can Large Reasoning Models Self-Train?](https://arxiv.org/abs/2505.21444) | Bakytzhan Alibekov |
| | | **Learning from agent experience** | | |
| 5 | 01-12-2026 | Learning to create and reuse skills | [Reinforcement Learning for Self-Improving Agent with Skill Library](https://arxiv.org/abs/2512.17102) | Fahad Khalid |
| 6 | 08-12-2026 | Optimizing prompts from experience | [GEPA: Reflective Prompt Evolution Can Outperform Reinforcement Learning](https://arxiv.org/abs/2507.19457) | He Zhu |
| | | **Task generation and curriculum learning** | | |
| 7 | 15-12-2026 | Generating verifiable training tasks | [Absolute Zero: Reinforced Self-play Reasoning with Zero Data](https://arxiv.org/abs/2505.03335) | Qilan Yu |
| – | 22-12-2026 | No class — Christmas break | | |
| – | 29-12-2026 | No class — Christmas break | | |
| 8 | 05-01-2027 | Learning to generate useful curricula | [Teaching Models to Teach Themselves: Reasoning at the Edge of Learnability](https://arxiv.org/abs/2601.18778) | Paulina Hussein |
| | | **Self-modifying agents** | | |
| 9 | 12-01-2027 | Modifying the agent's implementation | [Darwin Gödel Machine: Open-Ended Evolution of Self-Improving Agents](https://arxiv.org/abs/2505.22954) | Pedro |
| 10 | 19-01-2027 | Improving the research agent's own code | [Recursive self-improvement of AI research agents](https://arxiv.org/abs/2609.26457) | Shane John Paul Newton |
| | | **Evaluating self-improvement** | | |
| 11 | 26-01-2027 | Do self-modifications generalize? | [HarnessDev: Can LLMs Create and Evolve Their Own Agent Harness?](https://arxiv.org/abs/2609.01437) | Peter Harmer |
| | | **Risks of self-improvement** | | |
| 12 | 02-02-2027 | When self-improvement goes wrong | [Your Agent May Misevolve: Emergent Risks in Self-evolving LLM Agents](https://arxiv.org/abs/2509.26354) | Luis Cihlar |
{: .seminar-schedule}

</div>

## Related Research

### 2. Repeated sampling and answer selection

- [Shrinking the Generation-Verification Gap with Weak Verifiers](https://arxiv.org/abs/2506.18203)

### 3. What does RL actually learn?

- [Spurious Rewards: Rethinking Training Signals in RLVR](https://arxiv.org/abs/2506.10947)

### 4. Where does the reward come from?

- [TTRL: Test-Time Reinforcement Learning](https://arxiv.org/abs/2504.16084)

### 5. Learning to create and reuse skills

- [SkillsBench: Benchmarking How Well Agent Skills Work Across Diverse Tasks](https://arxiv.org/abs/2602.12670)

### 6. Optimizing prompts from experience

- [Agentic Context Engineering: Evolving Contexts for Self-Improving Language Models](https://arxiv.org/abs/2510.04618)

### 7. Generating verifiable training tasks

- [Toward Training Superintelligent Software Agents through Self-Play SWE-RL](https://arxiv.org/abs/2512.18552)

### 8. Learning to generate useful curricula

- [R-Zero: Self-Evolving Reasoning LLM from Zero Data](https://arxiv.org/abs/2508.05004)

### 9. Modifying the agent's implementation

- [Huxley-Gödel Machine: Human-Level Coding Agent Development by an Approximation of the Optimal Self-Improving Machine](https://arxiv.org/abs/2510.21614)

### 10. Improving the research agent's own code

- [Meta-Harness: End-to-End Optimization of Model Harnesses](https://arxiv.org/abs/2603.28052)

### 11. Do self-modifications generalize?

- [A Sober Look at Progress in Language Model Reasoning: Pitfalls and Paths to Reproducibility](https://arxiv.org/abs/2504.07086)

### 12. When self-improvement goes wrong

- [Reflections on Trusting Trust, Revisited: Contaminating Self-Modifying AI Coding Agents with Poisoned Benchmarks](https://arxiv.org/abs/2609.17817)

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

Due: 31 March 2027. Send me an email with the PDF attached,
with the subject line "Self-improving agents seminar term paper submission: [Your Name]".

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
