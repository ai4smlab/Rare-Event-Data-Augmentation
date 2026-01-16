[![License](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Last Commit](https://img.shields.io/github/last-commit/your-username/Rare-Event-Data-Augmentation)
![Repo Size](https://img.shields.io/github/repo-size/your-username/Rare-Event-Data-Augmentation)
![Python Version](https://img.shields.io/badge/python-3.9%2B-blue)
![GitHub Stars](https://img.shields.io/github/stars/your-username/Rare-Event-Data-Augmentation?style=social)

<div align="center">

# Rare-Event Data Augmentation  
## Agentic Ontology-Guided Synthetic Image Generation

**Author:** Alaa Khamis  

</div>

---

## 🧭 Project Overview

This repository accompanies the paper:

> **Agentic Ontology-guided Synthetic Image Generation for Rare-Event Data Augmentation: Wildlife–Traffic as a Case Study**,  
> submitted to **IEEE Access**.

The work addresses the challenge of **data scarcity in rare and safety-critical visual scenarios**, with a particular focus on **wildlife–traffic interactions**. Such events are highly stochastic, difficult to capture at scale, and often occur under adverse conditions (e.g., nighttime, fog, rural highways).

To address these limitations, the paper proposes an **agentic AI-based framework** that integrates:

- Semantic **ontology-guided instructions**
- Autonomous **image generation agents**
- **Closed-loop evaluation and refinement**
- **Large multimodal models (LMMs)** as judges
- Objective **no-reference image quality metrics**

The result is a **controllable, scalable, and self-improving synthetic data augmentation framework** that supports both reference-based and **referenceless image generation**.

---

## 🧠 Agentic AI Framework

<img src="images/Workflow.png" alt="Agentic AI Workflow" width="800px">

**Figure:** An agentic AI framework for ontology-guided synthetic image generation and evaluation.

---

## 🧩 Semantic Ontology

<img src="images/Ontolog.svg" alt="Ontology Class Diagram" width="800px">

**Figure:** Class diagram of the semantic ontology for wildlife–traffic image generation with examples.

📄 **OWL Specification:**  
- `images/Ontolog.owl`

---

## 🧪 Synthetic Image Generation Examples

<img src="images/Synthetic_images.png" alt="Synthetic Image Examples" width="800px">

**Figure:** Examples of generated images using a referenceless ontology-guided approach.

(a) GPT-5 synthesis  
(b) gpt-image-1 refinement  
(c) Recommendation-driven regeneration  
(d) Gemini 3 Pro synthesis  

---

## 📊 Sample Results & Brief Observations

- Referenceless ontology-guided generation outperforms reference-based pipelines in perceptual realism.
- Recommendation-driven regeneration is more effective than direct refinement.
- Gemini 3 Pro achieves near-parity with natural images in subjective realism.

---

## 🎯 Key Contributions

- Agentic AI framework for rare-event data augmentation  
- Ontology-guided semantic control for image synthesis  
- Referenceless generation with clear data lineage  
- Closed-loop evaluation and self-improvement  
- Robust performance across foundation models  

---

## 🚗 Use Cases

- Autonomous driving perception  
- Wildlife–vehicle collision prevention  
- ADAS and AV safety benchmarking  
- Synthetic dataset generation for rare events  
- Intelligent transportation systems research  

---

## 🔖 Citation

If you use this repository, please cite:

Khamis, A., “Agentic Ontology-guided Synthetic Image Generation for Rare-Event Data Augmentation: Wildlife–Traffic as a Case Study,” *submitted to IEEE Access*, 2025.

```bibtex
@article{khamis2025rare,
  title   = {Agentic Ontology-guided Synthetic Image Generation for Rare-Event Data Augmentation: Wildlife--Traffic as a Case Study},
  author  = {Khamis, Alaa},
  journal = {Submitted to IEEE Access},
  year    = {2025}
}
```
