## About The Project
This project provides a small-scale but fully functional Language Learning Model (LLM) built from scratch
using PyTorch. The model is specifically designed and trained on medical text from the `TheBlueScrubs-v1-fixed` dataset. 
It serves as a learning resource and a starting point for experimenting with LLM architectures, training techniques, and their application in specialized domains like medicine.

   
## Model Architecture and Metrics
   
The `MinimalLLM` is a decoder-only Transformer model with the following default parameters:   
| Parameter | Value | Description |
| :--- | :--- | :--- |
| `d_model` | 384 | The dimensionality of the model's embeddings. |
| `n_layers` | 6 | The number of Transformer blocks. |
| `n_heads` | 8 | The number of attention heads in each Transformer block. |
| `d_ff` | 1536 | The dimensionality of the feed-forward network. |
| `max_seq_len` | 512 | The maximum sequence length the model can process. |
| `vocab_size` | 50257 | Determined by the `HuggingFaceTB/SmolLM-135M` tokenizer. |
