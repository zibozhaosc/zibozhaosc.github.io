---
title: "TKGT: Redefinition and A New Way of Text-to-Table Tasks Based on Real World Demands and Knowledge Graphs Augmented LLMs" 
weight: 4
date: 2024-09-11
lastmod: 2024-10-19
tags: ["LLM","Knowledge Graph","Text-to-Table"]
author: ["Zibo Zhao", "Peiwen Jiang", "Xinbo Lin", "Ruhui Ma", "Yvonne Jie Chen", "Jinghua Cheng"]
description: "Accepted @ EMNLP2024 main session" 
summary: "Conference Publication-Artificial Intelligence Application to Textual Data Process for Chinese Legislation Document" 

---

---

##### Download

+ [Paper](TKGT_EMNLP2024.pdf)
+ [ACL Anthology](https://aclanthology.org/2024.emnlp-main.901/)
+ [Github Repo of TKGT and CPL Data](https://github.com/jiangpw41/TKGT)
---

##### Abstract

The task of text-to-table receives widespread attention, yet its importance and difficulty are underestimated. Existing works use simple datasets similar to table-to-text tasks and employ methods that ignore domain structures. As a bridge between raw text and statistical analysis, the text-to-table task often deals with complex semi-structured texts that refer to specific domain topics in the real world with entities and events, especially from those of social sciences.

In this paper, we analyze the limitations of benchmark datasets and methods used in the text-to-table literature and redefine the text-to-table task to improve its compatibility with long text-processing tasks. Based on this redefinition, we propose a new dataset called **CPL** (Chinese Private Lending), which consists of judgments from China and is derived from a real-world legal academic project. 

We further propose TKGT (**T**ext-**KG**-**T**able), a two-stage domain-aware pipeline, which firstly generates domain knowledge graphs (KGs) classes semi-automatically from raw text with the mixed information extraction (Mixed-IE) method, then adopts the hybrid retrieval augmented generation (Hybrid-RAG) method to transform it to tables for downstream needs under the guidance of KGs classes. 

Experiment results show that TKGT achieves state-of-the-art (SOTA) performance on both traditional datasets and the CPL. Our data and main code are available at [https://github.com/jiangpw41/TKGT](https://github.com/jiangpw41/TKGT).

---

##### Citation

Peiwen Jiang, Xinbo Lin, Zibo Zhao, Ruhui Ma, Yvonne Jie Chen, and Jinhua Cheng. 2024. TKGT: Redefinition and A New Way of Text-to-Table Tasks Based on Real World Demands and Knowledge Graphs Augmented LLMs. In Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing, pages 16112–16126, Miami, Florida, USA. Association for Computational Linguistics.

```BibTeX
@inproceedings{jiang-etal-2024-tkgt,
    title = "{TKGT}: Redefinition and A New Way of Text-to-Table Tasks Based on Real World Demands and Knowledge Graphs Augmented {LLM}s",
    author = "Jiang, Peiwen  and
      Lin, Xinbo  and
      Zhao, Zibo  and
      Ma, Ruhui  and
      Chen, Yvonne Jie  and
      Cheng, Jinhua",
    editor = "Al-Onaizan, Yaser  and
      Bansal, Mohit  and
      Chen, Yun-Nung",
    booktitle = "Proceedings of the 2024 Conference on Empirical Methods in Natural Language Processing",
    month = nov,
    year = "2024",
    address = "Miami, Florida, USA",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.emnlp-main.901",
    pages = "16112--16126",
    abstract = "The task of text-to-table receives widespread attention, yet its importance and difficulty are underestimated. Existing works use simple datasets similar to table-to-text tasks and employ methods that ignore domain structures. As a bridge between raw text and statistical analysis, the text-to-table task often deals with complex semi-structured texts that refer to specific domain topics in the real world with entities and events, especially from those of social sciences. In this paper, we analyze the limitations of benchmark datasets and methods used in the text-to-table literature and redefine the text-to-table task to improve its compatibility with long text-processing tasks. Based on this redefinition, we propose a new dataset called CPL (Chinese Private Lending), which consists of judgments from China and is derived from a real-world legal academic project. We further propose TKGT (Text-KG-Table), a two stages domain-aware pipeline, which firstly generates domain knowledge graphs (KGs) classes semi-automatically from raw text with the mixed information extraction (Mixed-IE) method, then adopts the hybrid retrieval augmented generation (Hybird-RAG) method to transform it to tables for downstream needs under the guidance of KGs classes. Experiment results show that TKGT achieves state-of-the-art (SOTA) performance on both traditional datasets and the CPL. Our data and main code are available at https://github.com/jiangpw41/TKGT.",
}
```
