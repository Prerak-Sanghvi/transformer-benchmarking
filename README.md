# Transformer Inference Benchmarking

This project benchmarks **BERT**, **DistilBERT**, and **Longformer** for sentiment classification on IMDB dataset.  
It compares inference speed across input sizes (256–4096 tokens) on a **Tesla T4 GPU**.

## Key Findings
- **DistilBERT** is ~5× faster than Longformer for short inputs.
- **Longformer** handles long sequences (4096 tokens), suitable for document-level tasks.
- Sentiment bias differences observed among models.


