# Morrow

Official implementation of **Morrow: A Morphology-Aware Subword Tokenizer**.

## Installation

```bash
pip install -r requirements.txt
```

## Repository structure

```
src/tokenizer.py
train_tokenizer.py
eval_tokenizer.py
requirements.txt
```

## Training

Run `python train.py --config configs/default.yaml` to reproduce the main results.
Checkpoints and logs are written to `runs/`.

## Evaluation

Run `python eval.py --checkpoint runs/latest` to reproduce the benchmark tables.

## Citation

```bibtex
@inproceedings{misc,
  title = {Morrow: A Morphology-Aware Subword Tokenizer},
  booktitle = {Proceedings of the corresponding venue},
  year = {2025}
}
```
