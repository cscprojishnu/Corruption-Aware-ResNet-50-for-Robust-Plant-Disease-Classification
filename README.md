# Corruption-Aware ResNet-50 for Robust Plant Disease Classification

> **An early-stage independent research project developed during the 2nd semester of my B.Tech.**

## About This Project

This repository contains my complete implementation and experimental work on **plant disease classification using ResNet-50**, with a particular focus on evaluating and improving model robustness against image corruptions.

The project started as my **first serious research-oriented machine learning project during the second semester of my B.Tech.** It was developed as an independent learning and experimentation effort, beginning with a conventional ResNet-50 baseline and gradually evolving into a study of model robustness under degraded image conditions.

The central idea of this work is simple:

> **Very high accuracy on clean images does not necessarily mean that a deep learning model is robust to corrupted or degraded inputs.**

To investigate this, I trained and evaluated two ResNet-50 models:

1. **Baseline ResNet-50** — trained using the standard training pipeline.
2. **Corruption-aware ResNet-50** — trained with augmentation strategies designed to improve robustness against image degradations.

Both models were evaluated under identical test conditions.

---

## Important Authorship / Project Statement

**This project, including the core research idea, experimental design, implementation, training pipeline, evaluation pipeline, error analysis, and robustness experiments, was conceived and implemented by me.**

The purpose of this repository is to document and preserve my early research work, experiments, code, results, and learning process.

This repository should therefore be treated as a record of my original implementation and research exploration.

I am **not currently publishing the associated research paper myself**. The paper/research write-up is being maintained primarily as documentation of the work performed during this project.

The repository is publicly available so that the implementation and experimental results can be inspected, reproduced, learned from, and built upon.

---

## Why I Started This Work

This project represents the **beginning of my research journey**.

At the time of developing this work, I was only in the **2nd semester of my B.Tech.** and had very limited prior experience with conducting machine-learning research.

Rather than beginning with a highly complex architecture or an extremely sophisticated research problem, I started with a well-established convolutional neural network and a standard agricultural image-classification dataset.

The project gradually evolved through experimentation:

```text
Plant Disease Classification
            ↓
      ResNet-50 Baseline
            ↓
    Clean Test Evaluation
            ↓
      Error Analysis
            ↓
 Identify Model Weaknesses
            ↓
   Image Corruption Testing
            ↓
 Corruption-Aware Training
            ↓
Baseline vs Robust Comparison
