# Cakap — Indonesian CS Conversational Model

Fine-tuning Gemma 4 (4B) for Indonesian-language customer service conversations using Unsloth.

## Training Pipeline
1. **Dataset** — 200 synthetic CS conversations generated with Claude Opus
2. **Fine-tuning** — Google Colab + Unsloth (LoRA, 4-bit quantization)
3. **Merge & Quantize** — Kaggle (Q8_0 GGUF)
4. **Publish** — HuggingFace

## Links
- 📦 Dataset: https://www.kaggle.com/datasets/rafikusuma/cs-dataset
- 🤗 Model: https://huggingface.co/rafkus/gemma4-cs-q8_0

## Requirements
- Python 3.10+
- Google Colab (GPU runtime)
- Unsloth, TRL, Transformers

## Usage
See `train.ipynb` for the full training script.
