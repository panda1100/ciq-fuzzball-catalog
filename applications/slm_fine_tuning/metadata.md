# Copyright 2025 CIQ, Inc. All rights reserved.
---
id: "slm_fine_tuning" # needs to be **unique** per application, changing results in a new application
name: "Small Language Model Fine Tuning Example"
category: "ML_AND_AI"
tags:
- SLM
- LLM
- ML-training
---
This workflow demonstrates an example usage pattern to fine tune an existing language model on a new data set. It contains jobs that carry out the following tasks.
- Downloading and preparing a dataset (Alpaca datase)
- Loading an existing model (Llama 3.1 8B model)
- Fine-tuning the model with LoRA on the new dataset using Unsloth
- Serving fine tuned model using Open WebUI with builtin Ollama