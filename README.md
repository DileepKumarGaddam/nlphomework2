# nlphomework2
#Dileep Kumar Gaddam #700775763
#  NLP Programming Assignment

This repository contains implementations of core Natural Language Processing (NLP) models and concepts, including RNNs and Transformers.

---

##  Contents

###  Q1: Character-Level RNN Language Model
- Built a character-level language model to predict the next character.
- Model pipeline:
- - Training:
- Teacher forcing
- Cross-entropy loss
- Adam optimizer
- Outputs:
- Training loss curve
- Generated text samples (temperature = 0.7, 1.0, 1.2)
- Key concepts:
- Sequence modeling
- Temperature sampling
- Teacher forcing

---

###  Q2: Mini Transformer Encoder
- Implemented a simplified Transformer Encoder (no decoder).
- Steps:- Tokenization and embedding
- Sinusoidal positional encoding
- Multi-head self-attention
- Feed-forward network
- Add & Norm (Residual + LayerNorm)
- Outputs:
- Input tokens
- Contextual embeddings
- Attention heatmap
- Key concepts:
- Self-attention
- Multi-head attention
- Positional encoding

---

###  Q3: Scaled Dot-Product Attention
- Implemented attention function:
- - Features:
- Random Q, K, V testing
- Attention weight matrix
- Output vectors
- Softmax stability check (before vs after scaling)
- Key concepts:
- Attention mechanism
- Scaling for numerical stability

---

## ⚙️ Requirements

- Python 3.x
- PyTorch
- NumPy
- Matplotlib (for visualization)                                                                                                                                                                                                             Install dependencies:
```bash
pip install torch numpy matplotlib
