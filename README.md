
# AIG 230 – Lab 05  
## Sequence Models with PyTorch: Learning from Ordered Text

### Overview

This lab introduces **sequence modeling**, a core concept in modern Natural Language Processing.
Unlike previous labs that treated text as unordered collections of words or standalone embeddings,
this lab focuses on models that **explicitly account for word order and temporal structure**.

You will work with **Recurrent Neural Networks (RNNs)** implemented in **PyTorch** to understand
how models process text one token at a time and learn representations that depend on context over time.

---

### Learning Objectives

By completing this lab, you will be able to:

- Explain why **word order** matters in NLP tasks
- Describe how **sequence models** differ from bag-of-words and embedding-only approaches
- Understand the structure and behavior of **Recurrent Neural Networks (RNNs)**
- Work with **sequence tensors** in PyTorch
- Trace how information flows across time steps in an RNN
- Interpret model outputs and loss values during training
- Connect sequence modeling to downstream NLP tasks

---

### Topics Covered

This lab builds on Week 4 and introduces foundational concepts for neural NLP models:

- Limitations of bag-of-words and static embeddings  
- Sequences and temporal dependencies in language  
- Recurrent Neural Networks (high-level intuition)  
- Hidden states and information flow over time  
- Input, hidden, and output representations  
- Tensor shapes for sequences and batches  
- Training loops for sequence models in PyTorch  
- Conceptual limitations of basic RNNs  

---

### Tools and Libraries

You will work with:

- **PyTorch** for building and training sequence models  
- **NLTK** for tokenization and basic preprocessing  
- **NumPy / Pandas** for data handling  
- **matplotlib** for visualizing training behavior  
- **Jupyter Notebook** for interactive experimentation  

---

### Dataset

The lab uses a **small text corpus** designed to emphasize **sequence behavior and model mechanics**
rather than large-scale performance.

The goal is to understand:

- How sequences are constructed
- How tokens are processed step by step
- How context accumulates across time

This mirrors how larger neural models process real-world text.

---

### Files in This Lab

- `AIG230_Week5_Lab_Sequence_Models.ipynb`  
  The main lab notebook.

  Includes:
  - Conceptual explanations
  - Fully commented PyTorch code
  - Shape and tensor walkthroughs
  - Training loop breakdowns
  - Checkpoint questions for understanding

- `SETUP.md`  
  Environment and installation instructions specific to Lab 05.

---

### Instructions

1. Use the provided template repository.
2. Create a repository named `aig230-lab05-yourname`.
3. Follow **SETUP.md** exactly before opening the notebook.
4. Complete the notebook:
   - Run all code cells
   - Answer **all checkpoint questions** in markdown cells
5. Commit and push your completed notebook to GitHub.
6. Submit the repository link on Blackboard.

---

### Expectations

- The notebook must run from top to bottom without errors.
- Do not delete or restructure code unless explicitly instructed.
- Written answers must be clear, concise, and in your own words.
- Focus on **understanding sequence behavior**, not model performance.

---

### Key Takeaway

This lab marks the transition from **static representations** to **dynamic models of language**.

Sequence models are the first step toward more powerful architectures such as
**attention mechanisms, transformers, and large language models**, which you will study next.

Understanding how information flows through time is essential for everything that follows.

---
