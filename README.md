# From Superposition to Sparse Autoencoders: Understanding Neural Feature Representations

**ML in PL 2025 Workshop Repository**

## Overview

This repository contains materials from the workshop "From Superposition to Sparse Autoencoders: Understanding Neural Feature Representations" presented at the ML in PL Conference 2025 on October 18th, 2025.

**Instructors:** Patryk Wielopolski and Taras Kutsyk

## Workshop Description

This workshop provides a comprehensive introduction to mechanistic interpretability through the lens of neural feature representations. Based on the acclaimed [ARENA curriculum](https://arena-chapter1-transformer-interp.streamlit.app/) by Callum McDougall, we focus on Chapter [1.3.1: Toy Models of Superposition & Sparse Autoencoders](https://arena-chapter1-transformer-interp.streamlit.app/[1.3.1]_Toy_Models_of_Superposition_&_SAEs#1-3-1-toy-models-of-superposition-and-sparse-autoencoders), which implements key findings from Anthropic's seminal paper ["Toy Models of Superposition"](https://transformer-circuits.pub/2022/toy_model/index.html).

### Abstract

Modern neural networks often learn representations that are difficult to interpret, with individual neurons responding to multiple unrelated features - a phenomenon called polysemanticity. This workshop explores the theoretical foundations and practical implications of how neural networks represent features through the lens of Anthropic’s influential “Toy Models of Superposition” paper. Participants will gain hands-on experience with the fundamental concepts of mechanistic interpretability by building and analyzing simple neural networks that demonstrate superposition - the ability of models to represent more features than they have dimensions. Through interactive exercises attendees will train toy models with varying sparsity levels and observe how networks organize features into geometric structures like antipodal pairs and pentagons when forced to compress high-dimensional feature spaces. The workshop concludes with an exploration of Sparse Autoencoders (SAEs) as a promising solution for disentangling features. Participants will implement and train their own SAEs on the toy models, visualizing how dictionary learning techniques can recover interpretable feature representations from seemingly incomprehensible neural activations. This workshop bridges theory and practice, providing both the mathematical intuition behind superposition phenomena and practical tools for investigating real neural network behavior - essential knowledge for anyone interested in AI safety, interpretability research, or understanding the inner workings of modern ML systems.

## Repository Contents

### 📊 Presentation Materials
- **File:** `Polysemanticity and Superposition in Neural Networks.pdf`
- **Topics Covered:**
  - AI Safety overview
  - Mechanistic Interpretability fundamentals
  - Sparse Autoencoders applications
  - Next steps in interpretability research

### 📓 Interactive Notebooks

#### Part 1: Toy Models of Superposition
- **File:** `TMS_Workshop_Part_1.ipynb`
- **Content:** Implementation and analysis of toy models demonstrating superposition phenomena

#### Part 2: Sparse Autoencoders
- **File:** `TMS_Workshop_Part_2_SAEs.ipynb`
- **Content:** Training and evaluating Sparse Autoencoders for feature disentanglement

## Getting Started

1. Clone this repository:
   ```bash
   git clone [repository-url]
   cd [repository-name]
   ```

2. Access the notebooks through the provided Colab links for immediate use, or run locally with:
   ```bash
   jupyter notebook
   ```

3. Review the presentation PDF for theoretical background before diving into the practical exercises.

## Prerequisites

- Basic understanding of neural networks and PyTorch
- Familiarity with Python programming
- Interest in AI interpretability and safety

## Learning Outcomes

By completing this workshop, participants will:
- Understand the concept of superposition in neural networks
- Gain practical experience with Toy Models of Superposition
- Learn to implement and train Sparse Autoencoders
- Develop skills for analyzing and visualizing neural network representations

## Additional Resources

- [ARENA Curriculum](https://arena-chapter1-transformer-interp.streamlit.app/)
- [Anthropic's Toy Models of Superposition Paper](https://transformer-circuits.pub/2022/toy_model/index.html)
- [Mechanistic Interpretability Resources](https://www.lesswrong.com/posts/LbrPTJ4fmABEdEnLf/mechinterp-reading-list)

## Contact

We welcome questions and feedback about the workshop materials:

- **Taras Kutsyk** - [LinkedIn Profile](https://www.linkedin.com/in/taras-kutsyk-135006212/)
- **Patryk Wielopolski** - [LinkedIn Profile](https://www.linkedin.com/in/patryk-wielopolski/)

## Acknowledgments

Special thanks to:
- Callum McDougall for the exceptional ARENA curriculum
- Anthropic for groundbreaking research in mechanistic interpretability
- ML in PL 2025 conference organizers

---

*Workshop presented at ML in PL 2025, October 18th, 2025*
