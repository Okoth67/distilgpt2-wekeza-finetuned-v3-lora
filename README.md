# DistilGPT2-Wekeza-Finetuned-v3-LoRA

This project fine-tunes the lightweight DistilGPT2 model using LoRA (Low-Rank Adaptation) to generate Kenya-specific financial and investment text responses. It is part of my personal learning journey into LLM fine-tuning, with a focus on hands-on implementation and self-instruction methods.

## 🔧 Project Details

- **Base Model**: [`distilgpt2`](https://huggingface.co/distilgpt2)
- **Method**: LoRA fine-tuning using PEFT
- **Task**: Financial Q&A generation
- **Dataset**: Custom instruction-style dataset (Alpaca-style) with Kenya-specific investment questions
- **Hardware**: CPU-friendly setup (no need for massive GPUs)
- **LoRA Output Dir**: `./distilgpt2-wekeza-finetuned_v3_lora`

## 📁 Contents

- `distilgpt2-wekeza-finetuned-v3-lora.ipynb` — training + generation notebook
- `WekezaLLM_dataset_v3.jsonl` — training dataset
