# Simorgh: A Transformer for English–Persian Neural Machine Translation

**Simorgh** is a research-oriented implementation of the Transformer architecture (Vaswani et al., 2017) applied to **English → Persian (Farsi)** neural machine translation.  
The system has been implemented **from first principles in PyTorch**, with a focus on clarity, modularity, and extensibility.

---

## Key Features
- **Complete Transformer architecture**: encoder–decoder stack with multi-head attention, feed-forward layers, residual connections, and layer normalization.
- **Custom embeddings and positional encodings** to support variable sequence lengths.
- **Xavier (Glorot) initialization** for stable optimization in deep architectures.
- Modular design enabling extension to other language pairs and tasks.
- Ready for integration with standard translation datasets (e.g., OPUS, Tatoeba, WMT).

---