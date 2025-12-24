# Llama-3.2-1B-MedQuAD-Fine-Tuning-LoRA-
This repository contains a parameter efficient fine tuning pipeline for a medical question answering assistant trained on the MedQuAD dataset. The project uses a LLaMA based instruction model fine tuned with LoRA to adapt it to real world medical question answer pairs sourced from trusted NIH platforms.
The training pipeline includes dataset preprocessing into structured system user assistant prompts, tokenizer alignment, causal language modeling supervision, and TPU compatible training using Hugging Face Transformers, PEFT, and Accelerate. The resulting model artifacts are saved in safe tensor format and are suitable for deployment or integration into retrieval augmented generation systems.

This project serves as a foundation for building reliable medical conversational agents, clinical decision support tools, and healthcare focused NLP applications under limited compute constraints.
