
Google – AI Assistants for Data Tasks with Gemma Using State-of-the-art Representation Fine-Tuning (ReFT) methods: A Powerful, Parameter-Efficient, and Interpretable fine-tuning method and Pytorch¶

In this competition, the goal is to create a notebook that demonstrates how to use the Gemma LLM to accomplish one of the following data science oriented tasks:

Explain or teach basic data science concepts.
Answer common questions about the Python programming language.
Summarize Kaggle solution write-ups.
Explain or teach concepts from Kaggle competition solution write-ups.
Answer common questions about the Kaggle platform.

Specifically, in this notebook, we are fine-tuning the Gemma 2B-it model with SOTA ReFT to answer common questions about the Python programming language.

TL;DR on ReFT: ReFT methods operate on a frozen base model and learn task-specific interventions on hidden representations. In this notebook, a strong instance of the ReFT family, Low-rank Linear Subspace ReFT (LoReFT) is employed. LoReFT is a drop-in replacement for existing PEFTs and learns interventions that are 10x-50x more parameter-efficient than prior state-of-the-art PEFTs. Explore further details in the paper.
