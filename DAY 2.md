### Neural Networks in Large Language Models (LLMs)
A neural network is a machine learning system inspired by the human brain that learns patterns from data using connected units called neurons (nodes).

### In LLMs, neural networks help to:
Understand human language
Learn relationships between words
Predict the next token (word/part of a word)

### Why Neural Networks Are Used in LLMs
Language is complex and pattern-based
Neural networks learn from massive text data
They improve predictions by learning from errors during training

### Types of Neural Networks

### 1️⃣ Artificial Neural Network (ANN)

### Description:
Basic structure: input → hidden → output layers
### Used for:
Simple prediction and classification
### Examples:
Spam email detection
Exam score prediction

### 2️⃣ Convolutional Neural Network (CNN)

### Description:
Designed for image and visual data
Detects patterns like edges and shapes
### Used for:
Image recognition
Face detection
📌 Note: CNNs are not used in LLMs

### 3️⃣ Recurrent Neural Network (RNN)
### Description:
Works with sequential data
Remembers previous inputs
### Used for:
Early NLP and speech models
### Limitation:
Poor performance with long context

### 🔤 Tokens in LLMs
### What Is a Token?
A token is the smallest unit of text an LLM processes.
### Tokens can be:
A full word
Part of a word
A character or symbol
### Why Tokens Matter
LLMs process tokens, not sentences
All text is converted into tokens first
Cost, speed, and limits depend on token count

### Tokenization
Tokenization is the process of breaking raw text into tokens before the model processes it.

### 🔄 Transformers in LLMs
### What Is a Transformer?

A Transformer is the core neural network architecture used in modern LLMs.

Unlike RNNs, Transformers process all tokens at once.

Why Transformers Are Powerful

Understand long sentences and documents

Capture complex word relationships

Faster training and inference

Highly scalable on large datasets

⚡ Parallelism in Transformers

All tokens are processed simultaneously

Uses self-attention and multi-head attention

Enables:

Faster training

Efficient GPU usage

Better scalability than RNNs
