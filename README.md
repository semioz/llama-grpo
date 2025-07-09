# LLaMA 3.1 GRPO Fine-Tuning with Unsloth

Fine-tuning LLaMA 3.1 8B Instruct model using [Unsloth](https://github.com/unslothai/unsloth) and the **Generalized Reinsertion Policy Optimization (GRPO)** algorithm from HuggingFace TRL.
Trained the model on reasoning tasks from the GSM8K dataset using custom reward functions and lightweight LoRA adapters.

---

- [Unsloth](https://github.com/unslothai/unsloth) for efficient 4-bit LoRA fine-tuning
-  **GRPO** (a reinforcement learning approach)
- [GSM8K](https://huggingface.co/datasets/openai/gsm8k) math reasoning tasks
- Custom reward functions (XML structure, integer answers, etc.) 
- vLLM for efficient inference and generation

---