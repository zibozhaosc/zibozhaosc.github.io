---
title: "Principled Understanding of Generalization for Generative Models in Arithmetic Reasoning Tasks" 
weight: 5
date: 2024-07-24
lastmod: 2025-05-30
tags: ["Machine Learning","Arithmetic Transformer", "Understanging the Ability of AI Models"]
author: ["Xingcheng Xu", "Zibo Zhao", "Haipeng Zhang", "Yanqing Yang"]
description: "Accepted @ ACL2025 main session" 
summary: "Conference Publication"

---

---

##### Download

+ [Paper](arithmetic_transformer_ood_theory.pdf)
+ [Arxiv Preprint](https://arxiv.org/pdf/2407.17963)
+ [Github Repo](https://github.com/xingchengxu/ArithmeticLLM)
---

##### Abstract

Transformer-based models excel in various tasks but their generalization capabilities, especially in arithmetic reasoning, remain incompletely understood. Arithmetic tasks provide a controlled framework to explore these capabilities, yet performance anomalies persist, such as inconsistent effectiveness in multiplication and erratic generalization in modular addition (e.g., modulo 100 vs. 101). This paper develops a unified theoretical framework for understanding the generalization behaviors of transformers in arithmetic tasks, focusing on length generalization. Through detailed analysis of addition, multiplication, and modular operations, we reveal that translation invariance in addition aligns with relative positional encoding for robust generalization, while base mismatch in modular operations disrupts this alignment. Experiments across GPT-family models validate our framework, confirming its ability to predict generalization behaviors. Our work highlights the importance of task structure and training data distribution for achieving data-efficient and structure-aware training, providing a systematic approach to understanding of length generalization in transformers.

---
