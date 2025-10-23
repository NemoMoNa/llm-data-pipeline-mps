# LLM Data Pipeline on Mac (MPS)

A minimal, inspectable LLM pipeline on Mac (MPS):
Raw → ChatTemplate → Tokenize → Labels (-100 mask) → Packing → 1-step train.

## Quickstart
```bash
python -m venv .venv && source .venv/bin/activate
pip install -U torch transformers datasets accelerate peft safetensors
jupyter lab
```
