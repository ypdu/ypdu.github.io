---
title: "LLM safety (UdS, Winter 2025)"
collection: courses
type: "Seminar"
permalink: /courses/llm-safety-seminar-2025/
semester: "Winter 2025"
level: "Master"
venue: "Saarland University"
date: 2025-10-01
location: "Saarbrücken, Germany"
---

## Course Description

Large language models (LLMs) are developing increasingly sophisticated reasoning abilities. 
More critically, they are becoming agentic—capable of autonomous decision-making and action-taking. 
This shift means humans are no longer the sole agents shaping outcomes in complex environments.

These advancements introduce significant challenges for ensuring safe and beneficial LLM behavior. 
Without proper safeguards, 
LLMs might generate unsafe contents or produce harmful behaviors; 
Moreover, they are vulnerable to various attacks,
which can be exploited by malicious actors to induce undesirable outcomes.
This seminar explores recent research studying these challenges, 
covering topics including privacy, interpretability, alignment, attacks, and evaluation.


## Prerequisites

This course assumes basic familiarity with NLP and ML, 
For example, you should be comfortable with, 
or be willing to learn about terms including but not limited to:
large language models, transformers, attention mechanisms, scaling laws, 
chain-of-thought reasoning, and reinforcement learning. 


## Information

<!-- - **registration form**: [Google form](https://forms.gle/jB8hU7AeaLRDqkpn7) -->
- **Instructor:** [Yupei Du](https://yupei.nl/) (yudo [at] lst [dot] uni-saarland [dot] de)
- **Time/Location:** Wed 14:15 - 15:45; Building C7.3, Room 1.14

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

| #  | Date       | Topic                        | Reading | Leader                                    |
| -- | ---------- | ---------------------------- | ------- | ----------------------------------------- |
| 1  | 15-10-2025 | Introduction                 |         | Yupei                                     |
| 2  | 22-10-2025 | PII extraction               |         | Yupei                                     |
| -  | 29-10-2025 | No class                     |         |                                           |
| -  | 05-11-2025 | No class                     |         |                                           |
| 3  | 12-11-2025 | Machine unlearning           |         | Cora Haiber, Betül Bahceci                |
| 4  | 19-11-2025 | Mechanistic interpretability |         | Katharina Trinley                         |
| 5  | 26-11-2025 | Data attribution             |         | Fabian Stiewitz                           |
| 6  | 03-12-2025 | Watermarking                 |         | Lotta Sophia Biedermann, Diego Torre Damm |
| 7  | 10-12-2025 | Alignment training           |         | Saugata Purkayastha                       |
| 8  | 17-12-2025 | Shallow vs. deep alignment   |         | Alena Tsanda, Barbare Tepnadze            |
| -  | 24-12-2025 | No class                     |         |                                           |
| -  | 31-12-2025 | No class                     |         |                                           |
| 9  | 07-01-2026 | Reward hacking               |         | Franka Beyer                              |
| 10 | 14-01-2026 | Prompt injection             |         | Houda Kaoukab, Zumrud Hasanova            |
| 11 | 21-01-2026 | Emergent misalignment        |         | Anthony Dsouza                            |
| 12 | 28-01-2026 | Benchmarks                   |         | Wojciech Stempniak                        |
| 13 | 04-02-2026 | Red-teaming                  |         | Harsha Rangadhamaiah                      |


## Suggested Readings

### Privacy 

**PII extraction:**

- Carlini et al., "Extracting Training Data from Large Language Models"  
- Huang et al., "Are Large Pre-Trained Language Models Leaking Your Personal Information?"
- Carlini et al., "Scalable Extraction of Training Data from (Production) Language Models"
- Lukas et al., "Analyzing Leakage of Personally Identifiable Information in Language Models"

**Machine unlearning:**

- Bourtoule et al., "Machine Unlearning"
- Graves et al., "Amnesiac Machine Learning" 
- Kurmanji et al., "Towards Unbounded Machine Unlearning"
- Foster et al., "Fast Machine Unlearning without Retraining through Selective Synaptic Dampening"

### Interpretability

**Mechanistic interpretability:**

- Vig et al., "Causal Mediation Analysis for Interpreting Neural NLP: The Case of Gender Bias"
- Nanda et al., "Progress Measures for Grokking via Mechanistic Interpretability"
- Meng et al., "Locating and Editing Factual Associations in GPT"
- Conmy et al., "Towards Automated Circuit Discovery for Mechanistic Interpretability"

**Data attribution:**

- Koh et al., "Understanding Black-box Predictions via Influence Functions"
- Ilyas et al., "Datamodels: Predicting Predictions from Training Data"
- Grosse et al., "Studying Large Language Model Generalization with Influence Functions"
- Bae et al., "Training Data Attribution via Approximate Unrolling"

**Watermarking:**

- Kirchenbauer et al., "A Watermark for Large Language Models"
- Dathathri et al., "Scalable watermarking for identifying large language model outputs
- Sander et al., "Watermarking makes language models radioactive"
- Zhang et al., "REMARK-LLM: A Robust and Efficient Watermarking Framework for Generative Large Language Models"

### Alignment 

**Alignment training:**

- Ouyang et al., "Training language models to follow instructions with human feedback"
- Bai et al., "Training a Helpful and Harmless Assistant with Reinforcement Learning from Human Feedback"
- Rafailov et al., "Direct Preference Optimization: Your Language Model is Secretly a Reward Model"
- Dai et al., "Safe RLHF: Safe Reinforcement Learning from Human Feedback"

**Shallow vs. deep alignment:**

- Arditi et al., "Refusal in Language Models Is Mediated by a Single Direction"
- Qi et al., "Fine-tuning Aligned Language Models Compromises Safety, Even When Users Do Not Intend To!"
- Qi et al., "Safety Alignment Should be Made More Than Just a Few Tokens Deep"

**Reward hacking:**

- Gao et al., "Scaling Laws for Reward Model Overoptimization"
- Wen et al., "Language Models Learn to Mislead Humans via RLHF"
- Baker et al., "Monitoring Reasoning Models for Misbehavior and the Risks of Promoting Obfuscation"
- Sharma et al., "Towards Understanding Sycophancy in Language Models"

### Attacks 

**Prompt injection:**

- Greshake et al., "Not what you've signed up for: Compromising Real-World LLM-Integrated Applications with Indirect Prompt Injection"
- Shi et al., "Lessons from Defending Gemini Against Indirect Prompt Injections"

**Emergent misalignment:**

- Betley et al., "Emergent Misalignment: Narrow finetuning can produce broadly misaligned LLMs"
- Wang et al., "Persona Features Control Emergent Misalignment"

### Evaluation

**Benchmarks:**

- Lin et al., "TruthfulQA: Measuring How Models Mimic Human Falsehoods"
- Hartvigsen et al., "ToxiGen: A Large-Scale Machine-Generated Dataset for Adversarial and Implicit Hate Speech Detection"
- Zhan et al., "InjecAgent: Benchmarking Indirect Prompt Injections in Tool-Integrated Large Language Model Agents"
- Maini et al., "TOFU: A Task of Fictitious Unlearning for LLMs"

**Red teaming:**

- Perez et al., "Red Teaming Language Models with Language Models"
- Casper et al., "Explore, Establish, Exploit: Red Teaming Language Models from Scratch"
- Chao et al., "Jailbreaking Black Box Large Language Models in Twenty Queries"
- Mehrotra et al., "Tree of Attacks: Jailbreaking Black-Box LLMs Automatically"


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
with the subject line "Safety seminar term paper submission: [Your Name]".

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
