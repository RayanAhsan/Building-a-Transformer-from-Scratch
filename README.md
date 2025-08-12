**Overview**

This project is a from-scratch implementation of the Transformer architecture introduced in the landmark paper Attention Is All You Need (Vaswani et al., 2017).
The goal was to understand and reproduce the core components of the Transformer without relying heavily on prebuilt high-level frameworks.

The implementation includes:
- Encoder–Decoder architecture
- Multi-Head Self-Attention
- Position-Wise Feed-Forward Networks
- Positional Encoding
- Masking (padding and look-ahead)

**Motivation**
  
When the Transformer paper was released, it reshaped the field of NLP by:

1. Removing recurrence entirely meaning no RNNs or LSTMs.
   
2. Demonstrating parallelizable training with self-attention.
   
3. Achieving state-of-the-art results in machine translation and more.

Instead of just using Transformers via Hugging Face or PyTorch APIs, I wanted to fully understand each layer mathematically and implement each module step-by-step (multi-head attention, feed-forward layers, etc.).
This was as much a learning experiment as it was a coding project. 
