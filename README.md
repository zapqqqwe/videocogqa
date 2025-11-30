
# 📘 VideoCogQA: A Controllable Benchmark for Evaluating Cognitive Abilities in Video-Language Models

**VideoCogQA** is a fully controllable benchmark designed to evaluate the **cognitive abilities** of Large Video-Language Models (LVLMs).
Unlike traditional real-world video datasets, VideoCogQA uses **programmatically generated synthetic videos**, providing fine-grained control over visual content, symbolic elements, temporal dynamics, and task difficulty.

This repository releases a **1k-sample subset** of VideoCogQA. The full paper is currently **under review**.

---

## 🔍 Overview

Recent advances in LVLMs have shown progress in multimodal perception, but it remains unclear whether these models possess genuine **high-level cognitive reasoning** capabilities. Existing video QA benchmarks often mix cognitive tasks with real-world noise, semantics, and uncontrolled difficulty, preventing clean evaluation.

**VideoCogQA addresses this gap** by offering:

* 🎮 **Synthetic videos from a programmatic engine**
  – complete control over all entities, attributes, motions, and interactions
* 🧠 **Cognitive-focused tasks**
  – abstract concepts, symbolic reasoning, temporal logic, multimodal composition
* 📈 **Difficulty-controlled settings**
  – isolate reasoning challenges from world knowledge

---

## 📦 Dataset Structure

Each instance includes a synthetic video and a multiple-choice reasoning question:

* **1,000** QA pairs
* Videos generated via Python-based game scenarios
* Difficulty is explicitly controlled
* All questions are designed to minimize reliance on prior world knowledge

---



## 📄 Citation

> *The VideoCogQA paper is currently under review. Citation metadata will be provided upon acceptance.*

---

## 🙏 Acknowledgments

VideoCogQA is created to support research on LVLM cognitive reasoning and provide a clean, controlled environment for testing symbolic and abstract problem-solving capabilities.

