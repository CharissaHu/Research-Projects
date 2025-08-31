# Research-Projects


# 📑 Text Distance from Nested and Hierarchical Repetitions: A Compression-Based Perspective

[![Paper投稿中，预印本](https://img.shields.io/badge/arXiv-preprint-red)](https://math.chinaxiv.org/abs/202506.00060)
[![Code](https://img.shields.io/badge/GitHub-Code-blue)](https://github.com/yuernestliu/lppack)

基于自研LP压缩算法提取无参数特征，设计轻量化kNN分类模型，在资源受限条件下实现95%文本分类准确率，部分任务性能超越BERT/CNN等深度神经网络模型，展示了该方法在NLP任务中的潜力。

---

## 📌 Abstract | 摘要
We present a new method for structural sequence analysis grounded in **Algorithmic Information Theory (AIT)**. At its core is the Ladderpath approach, which extracts nested and hierarchical relationships among repeated substructures in linguistic sequences---an instantiation of AIT’s principle of describing data through minimal generative programs. These structures are then used to define three distance measures: a normalized compression distance (NCD) and two alternative distances derived directly from the Ladderpath representation. Integrated with a $k$-nearest neighbor classifier, these distances achieve strong and consistent performance across in-distribution, out-of-distribution (OOD), and few-shot text classification tasks. In particular, all three methods outperform both gzip-based NCD and BERT under OOD and low-resource settings. These results demonstrate that the structured representations captured by Ladderpath preserve intrinsic properties of sequences and provide a lightweight, interpretable, and training-free alternative for text modeling. This work highlights the potential of AIT-based approaches for structural and domain-agnostic sequence understanding.

---

## 🎯 Keywords | 关键词

Algorithmic Information Theory (AIT) ｜ NLP | Normalized Compression Distance (NCD) ｜ Compression ｜ Ladderpath ｜ Text Classification ｜ Hierarchical Structure

---

## 🎯 Key Contributions | 主要贡献
- 作为第一作者，参与方法设计与建模，负责将LP算法与分类任务结合，构建完整实验流程。
- 设计并实现三种基于结构的**序列相似度度量方法**，结合KNN进行文本分类，验证模型在OOD与few-shot场景的泛化性能。
- 利用python处理200W+条文本数据，涉及11个多场景的NLP数据集，进行实验验证与对比分析，并在多个文本分类数据集上与主流大模型BERT、CNN等进行系统评估。
- 撰写论文摘要与实验部分，推动成果在学术场景中的展示
 

---


