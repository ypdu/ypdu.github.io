---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: false
---

You can also find my articles on <a href="https://scholar.google.com/citations?user=IgikFuEAAAAJ&hl=en-US">my Google Scholar profile</a>.

{% include base_path %}

## Selected Publications

(* indicates equal contribution)

- **_Reason to Rote: Rethinking Memorization in Reasoning._**
  EMNLP 2025.
  [[pdf]](https://arxiv.org/pdf/2507.04782)
  
  _Yupei Du_, Philipp Mondorf, Silvia Casola, Yuekun Yao, Robert Litschko, and Barbara Plank.
  
  **TL;DR:** We mechanistically study benign memorization in language models in reasoning tasks, and find that memorization does not replace but rather **is built on generalization**.

- **_Grokking ExPLAIND: Unifying Model, Data, and Training Attribution to Study Model Behavior._**
  arXiv preprint 2025.
  [[pdf]](https://arxiv.org/pdf/2505.20076)
  
  Florian Eichin, _Yupei Du_, Philipp Mondorf, Barbara Plank, Michael A. Hedderich.
  
  **TL;DR:** We introduce ExPLAIND—an interpretability framework for jointly attributing model components, data, and training dynamics and apply it to investigate Grokking.

- **_Language models can learn implicit multi-hop reasoning, but only if they have lots of training data._**
  EMNLP 2025.
  [[pdf]](https://www.arxiv.org/pdf/2505.17923)
  
  Yuekun Yao, _Yupei Du_, Dawei Zhu, Michael Hahn*, and Alexander Koller*.
  
  **TL;DR:** We studied the implicit multi-hop reasoning capabilities of language models, and find that they require an exponentially increasing amount of training data to perform well as the depth grows, and curriculum learning can substantially mitigate this.

- **_Disentangling the Roles of Representation and Selection in Data Pruning._**
  ACL 2025.
  [[pdf]](https://arxiv.org/pdf/2507.03648)
  
  _Yupei Du_, Yingjin Song, Hugh Mee Wong, Daniil Ignatev, Albert Gatt, and Dong Nguyen.
  
  **TL;DR:** We disentangled and systematically studied the influence of data representation and selection algorithm in data pruning.

- **_On Support Samples of Next Word Prediction._**
  ACL 2025.
  [[pdf]](https://arxiv.org/pdf/2506.04047)
  
  Yuqian Li*, <em>Yupei Du</em>*, Yufang Liu, Feifei Feng, Mou Xiao Feng, and Yuanbin Wu.
  
  **TL;DR:** We studied the training instances that support the predictions of language models, and reveal that supporting is likely an **intrinsic** property of data.

- **_Burn After Reading: Do Multimodal Large Language Models Truly Capture Order of Events in Image Sequences?_**
  Findings of ACL 2025.
  [[pdf]](https://arxiv.org/pdf/2506.10415)
  
  Yingjin Song, _Yupei Du_, Denis Paperno, and Albert Gatt.
  
  **TL;DR:** We propose a vision-language benchmark for multi-event temporal grounding and reasoning in image sequences.

- **_FTFT: Efficient and Robust Fine-Tuning by Transferring Training Dynamics._**
  COLING 2025.
  [[pdf]](https://arxiv.org/pdf/2310.06588.pdf)
  
  _Yupei Du_, Albert Gatt, and Dong Nguyen.
  
  **TL;DR:** We show that the training dynamics of an efficient but weak model can be **transferred** to much more capable models to achieve better robustness and efficiency.

- **_Understanding Gender Bias in Knowledge Base Embeddings._** ACL 2022. [[pdf]](https://aclanthology.org/2022.acl-long.98.pdf)
  
  _Yupei Du_, Qi Zheng, Yuanbin Wu, Man Lan, Yan Yang, Meirong Ma.
  
  **TL;DR:** We propose methods to **both quantify and trace the origins of gender biases** in knowledge base (embeddings), using a closed-form approximation of influence functions.

- **_Exploring Human Gender Stereotypes with Word Association Test._** EMNLP 2019. [[pdf]](https://www.aclweb.org/anthology/D19-1635.pdf)
  
  _Yupei Du_, Yuanbin Wu, Man Lan.
  
  **TL;DR:** We use label propagation to **quantify and visualize** how gender biases are transferred and reinforced through word associations, and therefore offer a large-scale dataset of word-level gender bias scores.

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
