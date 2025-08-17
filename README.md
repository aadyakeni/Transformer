# Transformer

# Transformer from Scratch – English → Spanish Translation

## Project Overview  
This project implements the **Transformer architecture from scratch** (no HuggingFace Trainer or high-level libraries) using **PyTorch**.  
It demonstrates how an encoder–decoder model can be built, trained, and evaluated for **machine translation** tasks.  

- **Input:** English sentence  
- **Output:** Spanish translation  

The model follows the original *Attention is All You Need* paper and includes:  
- Token/positional embeddings  
- Multi-head self-attention  
- Layer normalization & residual connections  
- Encoder–decoder attention  
- Feed-forward layers  
- Projection to vocabulary space  

---

## Features  
- From-scratch Transformer (no external seq2seq library)  
- **Opus Books (en–es)** dataset for English → Spanish translation  
- **Greedy decoding** for inference  
- Training & evaluation pipeline with:  
  - **BLEU Score** (translation quality)  
  - **Word Error Rate (WER)**  
  - **Character Error Rate (CER)**  
- Configurable hyperparameters (batch size, model size, sequence length)  
- TensorBoard logging for training visualization  

---

