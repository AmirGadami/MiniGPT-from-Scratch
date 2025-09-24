# Transformer from Scratch: English–Italian Neural Machine Translation

This project is a from-scratch implementation of the Transformer architecture (Vaswani et al., 2017) in PyTorch.  
It is applied to **English → Italian** neural machine translation and is designed for learning, research, and extensibility.

---

## Features

- Full Transformer architecture: encoder–decoder with multi-head attention, feed-forward layers, residual connections, and layer normalization
- Custom embeddings and sinusoidal positional encodings
- Xavier (Glorot) initialization for stable training
- Training and validation loops with checkpoint saving
- Integration with Hugging Face datasets and tokenizers
- Modular design for adapting to other sequence-to-sequence tasks

---

## Installation

Requirements:
- Python 3.10+
- PyTorch
- Hugging Face Datasets
- Hugging Face Tokenizers
- TensorBoard (optional)

Install dependencies:


---

## Training

Run:

```bash
python train.py
```

This will:
- Load the English–Italian dataset
- Train the Transformer model
- Save checkpoints in the specified folder

---

```

This will perform greedy decoding on the validation set and show sample translations.



---

## Reference

- Vaswani et al., "Attention Is All You Need", NeurIPS 2017

- [Coding a Transformer from scratch on PyTorch, with full explanation, training and inference. – Umar Jamil](https://www.youtube.com/watch?v=ISNdQcPhsts&t=5900s)
