# LLM-For-Story-Writing

## Finetuning mistral-7b-bnb-4bit(language model) with unsloth (low code fine-tune library)

1) loading a model with FastLanguageModel from unsloth libarary.
2) performing model patching using FastLanguageModel.get_peft_model.
3) Importing dataset from Hugging-face & storeing it in a trainable format to be given as input while fine-tuning.
4) Fine tuning model using SFTTrainer(Tokennizer), which includs optimizer & lora (to speed up process & reduce memory)
