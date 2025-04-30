PyTorch RNN-Based Question Answering System
===========================================

This project implements a simple RNN-based Question Answering (QA) system using PyTorch. 
It demonstrates the process of extracting answers from a given context based on a question, using sequence modeling techniques.

Project Overview
----------------
- Task: Extract the answer span from a paragraph given a question.
- Approach: Recurrent Neural Network (RNN) with Embedding and GRU layers.
- Framework: PyTorch
- Dataset: Custom or small context-question pairs for demonstration purposes.

Key Features
------------
- Text Preprocessing: Tokenization, vocabulary building, word-to-index and index-to-word mappings.
- Model Architecture:
    * Embedding Layer
    * GRU Layer
    * Linear Layers for start and end position predictions
- Training Pipeline:
    * Loss Function: CrossEntropyLoss
    * Optimizer: Adam
    * Accuracy tracking for start and end prediction
- Evaluation:
    * Given a question and context, the model predicts the most probable answer span.

Requirements
------------
- Python 3.x
- PyTorch
- NLTK
- Jupyter Notebook (optional, for running interactively)

Install required packages with:
    pip install torch nltk

Example Workflow
----------------
1. Provide a paragraph as context.
2. Ask a question related to the context.
3. The model returns the predicted answer span.

Example:
Context: "Sherlock Holmes was known for his detective skills..."
Question: "Who was known for detective skills?"
Answer: "Sherlock Holmes"

File Structure
--------------
PyTorch_rnn_based_QA_System.ipynb  - Full notebook with model, data processing, training, and testing
README.txt                         - Notes and documentation (this file)

Next Steps & Improvements
--------------------------
- Train on larger datasets like SQuAD for better performance
- Use LSTM instead of GRU or upgrade to Transformer models
- Add attention mechanism for more context awareness

Author
------
Prince Kumar
LinkedIn: https://www.linkedin.com/in/prince-kumar-23pri/

