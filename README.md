# BERT Mini Notebooks

A compact set of Jupyter notebooks that walk from **tokenization → embeddings → attention → residual+norm → pooler → MLM** with minimal, runnable examples.

## Files

* `00_bert_model_architecture_params.ipynb` — Key BERT hyperparameters.
* `02_no_grad_requires_grad.ipynb` — Autograd: `requires_grad`, `no_grad()`, `detach()`.
* `03_bert_embedding.ipynb` — Token/position/segment embeddings basics.
* `03_bert_input_embedding.ipynb` — Combine embeddings into BERT input tensors.
* `04_subword_wordpiece_tokenizer.ipynb` — WordPiece: tokenize/encode/decode.
* `05_model_outputs.ipynb` — HF outputs: `last_hidden_state`, `pooler_output`, etc.
* `06_attention.ipynb` — Scaled dot-product & multi-head attention.
* `07_add_norm_residual_conn.ipynb` — Residual + LayerNorm (pre/post-norm).
* `08_bert_head_pooler_output.ipynb` — Pooler path and simple classifier head.
* `09_masked_lm.ipynb` — 15% masking rule, loss, and a tiny MLM loop.

## Setup

Reference Environment
* Python 3.10.18
* PyTorch 2.8.0
* ...
* Packages:

```bash
pip install -r requirements.txt
```

## Quick Start

```bash
jupyter notebook
```

## Credits
Portions of this project are adapted from
[bilibili_vlogs](https://github.com/chunhuizhang/bilibili_vlogs).    
© Original copyright to the respective author(s). All rights reserved unless otherwise stated.
