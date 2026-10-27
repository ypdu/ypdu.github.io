---
title: "Towards Self-Improving Agents (UdS, Winter 26/27)"
collection: courses
published: false
type: "Seminar"
permalink: /courses/self-improving-agents-seminar-winter-26/
semester: "Winter 26/27"
level: "Master"
venue: "Saarland University"
date: 2026-10-27
location: "Saarbrücken, Germany"
---

## Course Description

How can language-model agents improve through their own attempts, feedback, and experience? This seminar studies concrete approaches to this question, focusing on how they work, what researchers have tried, and what the experimental evidence supports.

We begin with **reasoning and inference-time computation**: how much can repeated sampling improve performance, and what changes when a model is trained with reinforcement learning? We then move to **learning from interaction**, examining the challenges of multi-turn agent training and the acquisition of reusable skills. Next, we study **automated improvement**: generating training tasks, learning useful curricula, and optimizing an agent's prompts and code. Finally, we ask **how to establish that an agent has improved**, including fair comparisons, transfer to new tasks, retention of experience, and the limits of current evidence for recursive self-improvement.

Throughout the course, we distinguish better answers obtained through additional computation from changes that persist across tasks. Our emphasis is on concrete algorithms, examples, experiments, and limitations.

## Prerequisites

This course assumes a solid background in NLP and machine learning, including familiarity with language models and neural-network training. Basic knowledge of reinforcement learning is helpful; the introductory session will review the concepts needed for the seminar.

The readings can be technical. You are not expected to understand every detail of every paper, but you should be able to explain the main ideas and discuss the evidence critically. Large-scale model training is not required.

## Information

- **Instructor:** [Yupei Du](https://ypdu.github.io/) (yudo [at] lst [dot] uni-saarland [dot] de)
- **Time:** Tuesdays, 16:15–17:45
- **Location:** Gebäude C7 3 - Seminarraum 1.14
- **Language:** English
- **First meeting:** 27 October 2026
- **Introduction slides:** [Course overview and background](https://docs.google.com/presentation/d/1NbojB0-V0Ef_5V2rAyjQIw5ZsWOLd6Shs9XudmM4Uis/edit)
- **No class:** 3 November, 22 December, and 29 December 2026

## Format/Requirements

Each week, we will discuss one topic through one or two papers. One or two students will lead the session, with approximately 45–60 minutes of presentation and worked examples and the remaining 30–45 minutes for discussion, for a total of 90 minutes. Questions and discussion are welcome throughout the presentation.

The first meeting introduces the course and the necessary background. DeepSeek-R1 and Reflexion will be introduced briefly in that meeting. The student-led sessions begin with inference-time computation and the empirical debate about what reinforcement learning learns.

### For presenters

Your presentation should explain the problem, the proposed approach, and the evidence for its effectiveness. In particular, include:

- A concrete task, input/output example, or agent trajectory.
- A clear explanation of what is updated: model weights, memory, skills, prompts, code, or training data.
- The source of feedback and how the method uses it.
- One central result and a meaningful baseline or ablation.
- A limitation and a question for discussion.

Make the presentation accessible to students who have not worked on the topic. You do not need to cover every equation or experiment. Spend time explaining the mechanism and interpreting the results, including the computational budget and the distinction between training, model selection, and final testing.

When two students lead a session, they may present one paper each or divide the work between a main presentation and a comparison, worked example, or critical discussion. Regularly pause for questions and invite the audience to challenge the paper's assumptions.

The suggested readings are not exhaustive. You are welcome to propose another relevant paper; please email your suggestion at least **one week before the session**. Send the final slides and other materials afterwards for archiving.

### For audience

Read the main paper before class. All students are expected to ask questions and actively participate in the discussion.

Participation will be assessed using the following scale:

- **0:** Not engaged.
- **1:** Asked questions or made comments.
- **2:** Asked high-quality questions or made thoughtful comments.

## Syllabus

The schedule contains 12 meetings, including the introduction. Readings and presentation assignments may be adjusted during the semester. A paper marked *optional* is further reading, not an additional required presentation.

| # | Date | Topic | Reading | Leader |
| -- | -- | -- | -- | -- |
| 1 | 27-10-2026 | Introduction: reasoning, agents, and improvement | [Slides](https://docs.google.com/presentation/d/1NbojB0-V0Ef_5V2rAyjQIw5ZsWOLd6Shs9XudmM4Uis/edit) | Yupei |
| – | 03-11-2026 | No class | | |
| **A** | | **Reasoning and inference-time computation** | | |
| 2 | 10-11-2026 | Repeated sampling and answer selection | [Large Language Monkeys: Scaling Inference Compute with Repeated Sampling](https://arxiv.org/abs/2407.21787) | TBD |
| 3 | 17-11-2026 | What does RL actually learn? | [Does Reinforcement Learning Really Incentivize Reasoning Capacity in LLMs Beyond the Base Model?](https://arxiv.org/abs/2504.13837)<br>[Reinforcement Learning with Verifiable Rewards Implicitly Incentivizes Correct Reasoning in Base LLMs](https://arxiv.org/abs/2506.14245) | TBD |
| **B** | | **Learning from agent experience** | | |
| 4 | 24-11-2026 | From single-turn RL to multi-turn agents | [RAGEN: Understanding Self-Evolution in LLM Agents via Multi-Turn Reinforcement Learning](https://arxiv.org/abs/2504.20073) | TBD |
| 5 | 01-12-2026 | Learning to create and reuse skills | [Reinforcement Learning for Self-Improving Agent with Skill Library](https://arxiv.org/abs/2512.17102) (SAGE) | TBD |
| **C** | | **Automated improvement** | | |
| 6 | 08-12-2026 | Generating verifiable training tasks | [Absolute Zero: Reinforced Self-play Reasoning with Zero Data](https://arxiv.org/abs/2505.03335) | TBD |
| 7 | 15-12-2026 | Learning to generate useful curricula | [Teaching Models to Teach Themselves: Reasoning at the Edge of Learnability](https://arxiv.org/abs/2601.18778) (SOAR) | TBD |
| – | 22-12-2026 | No class — Christmas break | | |
| – | 29-12-2026 | No class — Christmas break | | |
| 8 | 05-01-2027 | Optimizing prompts from experience | [GEPA: Reflective Prompt Evolution Can Outperform Reinforcement Learning](https://arxiv.org/abs/2507.19457) | TBD |
| 9 | 12-01-2027 | Modifying the agent's implementation | [Darwin Gödel Machine: Open-Ended Evolution of Self-Improving Agents](https://arxiv.org/abs/2505.22954) | TBD |
| **D** | | **Evidence for self-improvement** | | |
| 10 | 19-01-2027 | Evaluating improvements fairly | [AI Agents That Matter](https://arxiv.org/abs/2407.01502) | TBD |
| 11 | 26-01-2027 | Transfer, interference, and forgetting | [PATH-Bench: Path-Dependent Evaluation of Lifelong Agents](https://arxiv.org/abs/2608.01149) | TBD |
| 12 | 02-02-2027 | Recursive improvement: evidence and open questions | [Recursive self-improvement of AI research agents](https://arxiv.org/abs/2609.26457) (AIDE²) | TBD |

## Suggested Readings

The main readings appear in the schedule. The questions below indicate the focus of each session; optional readings provide background or a comparison. PATH-Bench and AIDE² are recent 2026 preprints, which we will discuss with particular attention to their experimental design and limitations.

### A. Reasoning and inference-time computation

**2. Repeated sampling and answer selection**

How does performance change when a fixed model makes more attempts? What is the difference between generating a correct candidate and selecting it? Compare pass@1, pass@k, selected-answer accuracy, and computational cost.

- **Main:** [Large Language Monkeys](https://arxiv.org/abs/2407.21787).
- **Optional:** [Scaling LLM Test-Time Compute Optimally can be More Effective than Scaling Model Parameters](https://arxiv.org/abs/2408.03314).

**3. What does RL actually learn?**

Does RL make existing successful behavior more likely, broaden the range of solvable problems, or improve the validity of reasoning? Compare the two papers' definitions of capability, correctness criteria, and sampling budgets. Distinguish answer-based pass@k from CoT-Pass@k, and examine how errors in the reasoning judge affect the conclusions.

- **Main:** [Does Reinforcement Learning Really Incentivize Reasoning Capacity in LLMs Beyond the Base Model?](https://arxiv.org/abs/2504.13837).
- **Main:** [Reinforcement Learning with Verifiable Rewards Implicitly Incentivizes Correct Reasoning in Base LLMs](https://arxiv.org/abs/2506.14245).

### B. Learning from agent experience

**4. From single-turn RL to multi-turn agents**

What changes when a model must interact with an environment over multiple steps? Discuss credit assignment, exploration, rollout diversity, and training stability. Distinguish generated actions from observations supplied by the environment.

- **Main:** [RAGEN](https://arxiv.org/abs/2504.20073).
- **Optional:** [Agent Lightning: Train ANY AI Agents with Reinforcement Learning](https://arxiv.org/abs/2508.03680).

**5. Learning to create and reuse skills**

How can experience from one task become an executable skill used on another? Examine what is stored, how it is retrieved, and which experiments demonstrate useful transfer. Separate improvements from RL training from improvements due to accumulated skills at deployment.

- **Main:** [Reinforcement Learning for Self-Improving Agent with Skill Library](https://arxiv.org/abs/2512.17102) (SAGE).
- **Background:** [Voyager: An Open-Ended Embodied Agent with Large Language Models](https://arxiv.org/abs/2305.16291).

### C. Automated improvement

**6. Generating verifiable training tasks**

Can a system generate its own training problems and check the answers? Trace the task-generation and verification loop, and examine the remaining sources of human-designed structure and supervision.

- **Main:** [Absolute Zero](https://arxiv.org/abs/2505.03335).
- **Optional:** [Agent0: Unleashing Self-Evolving Agents from Zero Data via Tool-Integrated Reasoning](https://arxiv.org/abs/2511.16043).

**7. Learning to generate useful curricula**

What makes a generated problem useful for learning? Examine how SOAR rewards a teacher using the student's measured progress, and distinguish the questions used to compute that reward from the final test set.

- **Main:** [Teaching Models to Teach Themselves: Reasoning at the Edge of Learnability](https://arxiv.org/abs/2601.18778) (SOAR).

**8. Optimizing prompts from experience**

How can execution traces guide prompt changes? Follow an actual proposed edit and examine how candidates are selected, what transfers, and how repeated optimization can overfit an evaluation set.

- **Main:** [GEPA: Reflective Prompt Evolution Can Outperform Reinforcement Learning](https://arxiv.org/abs/2507.19457).

**9. Modifying the agent's implementation**

What can improve when an agent modifies its tools or workflow while its underlying language model stays fixed? Examine concrete code changes, the role of the archive, and the cost of searching for improvements.

- **Main:** [Darwin Gödel Machine: Open-Ended Evolution of Self-Improving Agents](https://arxiv.org/abs/2505.22954).

### D. Evidence for self-improvement

**10. Evaluating improvements fairly**

How should we compare agents with different inference budgets and development costs? Examine simple baselines, held-out evaluation, and benchmark implementation. Design a control experiment for a paper discussed earlier in the seminar.

- **Main:** [AI Agents That Matter](https://arxiv.org/abs/2407.01502).
- **Optional:** [SWE-Bench Pro: Can AI Agents Solve Long-Horizon Software Engineering Tasks?](https://arxiv.org/abs/2509.16941).

**11. Transfer, interference, and forgetting**

Does accumulating experience help on later tasks, and do earlier gains persist? Study evaluation along task sequences, including helpful and interfering histories, and explain why evaluation probes should not themselves update the agent's memory.

- **Main:** [PATH-Bench: Path-Dependent Evaluation of Lifelong Agents](https://arxiv.org/abs/2608.01149).

**12. Recursive improvement: evidence and open questions**

Can an agent become better at producing its own successors? Distinguish improvements in task performance from improvements in the process that creates the next agent, and assess what the experiments establish.

- **Main:** [Recursive self-improvement of AI research agents](https://arxiv.org/abs/2609.26457) (AIDE²).

### Background for the introductory meeting

These readings provide background and are not separate student presentation assignments.

- [Chain-of-Thought Prompting Elicits Reasoning in Large Language Models](https://arxiv.org/abs/2201.11903).
- [ReAct: Synergizing Reasoning and Acting in Language Models](https://arxiv.org/abs/2210.03629).
- [DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning](https://arxiv.org/abs/2501.12948).
- [Reflexion: Language Agents with Verbal Reinforcement Learning](https://arxiv.org/abs/2303.11366).

## Term paper (for the 7 CP version)

Students taking the 7-credit version will write either a survey on a topic relevant to the course or a small, well-executed independent project.

For a **survey**, identify a focused research question and compare at least three relevant papers. Explain their methods, assumptions, and evaluation settings, and assess where their findings agree or differ. Organize the discussion around the research question rather than presenting a sequence of unrelated summaries.

For an **independent project**, formulate a specific question and design manageable experiments to address it. Possible projects include comparing sampling and selection strategies under a fixed budget, testing skill reuse on related and unfamiliar tasks, examining a task-generation strategy, or evaluating transfer and forgetting in an agent with memory. Reproductions and careful negative results are welcome. Expensive model training is not required.

### Format

Up to **10 pages**, excluding references and appendices, using a NeurIPS paper template. Submit a PDF. There is no strict minimum length; the paper should be clear, consistent, and self-contained. Typst or LaTeX is recommended.

### Submission deadline

**31 March 2027.** Submit by email with the subject line: "Self-improving agents seminar term paper submission: [Your Name]".

### LLM use policy

You may use LLMs and other AI tools for learning and preparing your work, but **any use of AI tools must be clearly documented**. You remain fully responsible for the content of your presentation and paper, including the correctness of claims, experiments, and references. Verify generated material and explain the methods and results in your own words. Logical flaws, plagiarism, fabricated citations, and unsupported experimental claims affect the assessment regardless of how they were produced.

## Evaluation

*Study programs may differ in which credit versions are available; check with your study program coordinator if in doubt.*

| Component | 4 credits | 7 credits |
| -- | -- | -- |
| Presentation | 60% | 30% |
| Participation | 40% | 20% |
| Term paper | — | 50% |

## Contact

For questions about the course, please contact Yupei at yudo [at] lst [dot] uni-saarland [dot] de.
