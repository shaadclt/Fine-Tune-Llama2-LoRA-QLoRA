# Fine-tuneing Llama2 using LoRA and QLoRA

This repository contains the code for fine-tuning the Llama-2-7b-chat model on a text instruction dataset using LoRA (Layer-wise Only Relevant Attention) and QLoRA (Quantized LoRA).

## Features

- Fine-tunes Llama-2-7b-chat for improved performance on text instruction tasks
- Leverages LoRA for efficient parameter sharing
- Utilizes QLoRA for reduced memory footprint during training and inference

## Installation

```Bash
pip install -q accelerate==0.21.0 peft==0.4.0 bitsandbytes==0.40.2 transformers==4.31.0 trl==0.4.7
```

## Usage

1. Clone this repository.
2. Run the code in the notebook one by one.
