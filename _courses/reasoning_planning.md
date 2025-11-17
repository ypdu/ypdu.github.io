---
title: "Towards agentic LLMs that reason and plan (UdS, Winter 2025)"
collection: courses
type: "Seminar"
permalink: /courses/reasoning-planning-seminar-2025/
semester: "Winter 2025"
level: "Master"
venue: "Saarland University"
date: 2025-10-14
location: "Saarbrücken, Germany"
---

## Course Description

[New]: [link for showing interest](https://forms.gle/jB8hU7AeaLRDqkpn7)

Recent breakthroughs in reasoning and planning have further extended the capabilities of LLMs, 
enabling frontier models like GPT-5 to solve complex mathematical problems, 
and plan multi-step solutions to real-world software engineering tasks. 
These advances represent a pivotal shift from viewing LLMs merely as information sources 
to recognizing them as practical, real-world problem-solving systems.
This seminar series explores recent developments in LLM reasoning and planning capabilities, 
highlighting their potential for creating useful agents that assist in various complex tasks. 


## Prerequisites

This course assumes basic familiarity with NLP and ML, 
For example, you should be comfortable with, 
or be willing to learn about terms including but not limited to:
large language models, transformers, attention mechanisms, scaling laws, 
chain-of-thought reasoning, and reinforcement learning. 


## Information

<!-- - **registration form**: [Google form](https://forms.gle/jB8hU7AeaLRDqkpn7) -->
- **Instructor:** [Yupei Du](https://yupei.nl/) (yudo [at] lst [dot] uni-saarland [dot] de)
- **Time/Location:** Tue 16:15 - 17:45; Building C7.3, Room 1.12

## Format/Requirements

Each week, we will meet to discuss the assigned topic (see Syllabus). 
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
as long as they are related to the topic of the seminar! 
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
- 2 (asked high-quality questions or made thoughtful comments).


## Syllabus

| Session | Date       | Topic                | Reading | Leader                 |
| ------- | ---------- | -------------------- | ------- | ---------------------- |
|       1 | 21-10-2025 | Introduction         |         | Yupei                  |
|       2 | 28-10-2025 | No class             |         |                        |
|       3 | 04-11-2025 | No class             |         |                        |
|       4 | 11-11-2025 | Prompting            | [[ICML24] Premise Order Matters in Reasoning with Large Language Models](https://arxiv.org/abs/2402.08939) | Dhairushi Patel |
|       5 | 18-11-2025 | Learning to reason 1 | [[NeurIPS22] STaR: Bootstrapping Reasoning With Reasoning](https://arxiv.org/abs/2203.14465) | Anthony Dsouza |
|       6 | 25-11-2025 | Learning to reason 2 |         | Yonghua Huang          |
|       7 | 02-12-2025 | Long-context 1       |         | Quanzi Ma              |
|       8 | 09-12-2025 | Long-context 2       |         | Shane John Paul Newton |
|       9 | 16-12-2025 | Planning             |         | Fanyi Meng             |
|      10 | 23-12-2025 | No class             |         |                        |
|      11 | 30-12-2025 | No class             |         |                        |
|      12 | 06-01-2026 | Agents: foundation 1 |         | Ghazal Tajik           |
|      13 | 13-01-2026 | Agents: foundation 2 |         | Hongxu Zhou            |
|      14 | 20-01-2026 | Agents: planning     |         | Sree Harsha Sunaye     |
|      15 | 27-01-2026 | Agents: memory       |         | Pranav Kushare         |
|      16 | 03-02-2026 | Agents: benchmarks   |         | Diego Torre Damm       |



## Suggested Readings

### Prompting
<!-- - Wei et al., "Chain-of-Thought Prompting Elicits Reasoning in Large Language Models" -->
- Kojima et al., "Large Language Models are Zero-Shot Reasoners" 
- Yao et al., "Tree of Thoughts: Deliberate Problem Solving with Large Language Models"
- Wang et al., "Self-Consistency Improves Chain of Thought Reasoning in Language Models"
- Chen et al., "Program of Thoughts Prompting: Disentangling Computation from Reasoning for Numerical Reasoning Tasks"
- Chen et al., "Premise Order Matters in Reasoning with Large Language Models"

### Learning to reason
- Zelikman et al., "STaR: Bootstrapping Reasoning With Reasoning"
- Lightman et al., "Let’s Verify Step by Step"
- DeepSeek-AI et al., "DeepSeek-R1: Incentivizing Reasoning Capability in LLMs via Reinforcement Learning" 
- Muennighoff et al., "s1: Simple test-time scaling"
- Geiping et al., "Scaling up Test-Time Compute with Latent Reasoning: A Recurrent Depth Approach"
- Aggarwal and Welleck, "L1: Controlling How Long A Reasoning Model Thinks with Reinforcement Learning"
- Li et al., "LLMs Can Easily Learn to Reason from Demonstrations Structure, not content, is what matters!"

### Long-context

- Kazemnejad et al., "The Impact of Positional Encoding on Length Generalization in Transformers"
- Peng et al., "YaRN: Efficient Context Window Extension of Large Language Models"
- Sun et al., "Retentive Network: A Successor to Transformer for Large Language Models"
- Yang et al., "Parallelizing Linear Transformers with the Delta Rule over Sequence Length" 
- Sun et al., "Learning to (Learn at Test Time): RNNs with Expressive Hidden States"
- Behrouz et al., "Titans: Learning to Memorize at Test Time"

### Planning

- Lehnert et al., "Beyond A*: Better Planning with Transformers via Search Dynamics Bootstrapping"
- Ye et al., "Beyond Autoregression: Discrete Diffusion for Complex Reasoning and Planning"
- Silver et al., "Generalized Planning in PDDL Domains with Pretrained Large Language Models"

### Agents

**Foundation**
- Schick et al., "Toolformer: Language Models Can Teach Themselves to Use Tools"
- Yao et al., "ReAct: Synergizing Reasoning and Acting in Language Models"
- Yao et al., "WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents"
- Shinn et al., "Reflexion: Language Agents with Verbal Reinforcement Learning"
- Shen et al., "HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face"

**Planning**
- Liu et al., "LLM+P: Empowering Large Language Models with Optimal Planning Proficiency"
- Gu et al., "Is Your LLM Secretly a World Model of the Internet? Model-Based Planning for Web Agents"
- Wang et al., "PromptAgent: Strategic Planning with Language Models Enables Expert-level Prompt Optimization"

**Memory** 
- Packer et al., "MemGPT: Towards LLMs as Operating Systems"
- Zhong et al.,"MemoryBank: Enhancing Large Language Models with Long-Term Memory"
- Gutiérrez et al, "HippoRAG: Neurobiologically Inspired Long-Term Memory for Large Language Models"

**Benchmarks:**
- Zhou et al., "WebArena: A Realistic Web Environment for Building Autonomous Agents"
- Jimenez et al., "SWE-bench: Can Language Models Resolve Real-World GitHub Issues?"
- Deng et al., "Mind2Web: Towards a Generalist Agent for the Web"
- Xie et al., "OSWorld: Benchmarking Multimodal Agents for Open-Ended Tasks in Real Computer Environments"


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
Due: March end, 2026. Send me an email with the PDF attached, 
with the subject line "Reasoning seminar term paper submission: [Your Name]".

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
