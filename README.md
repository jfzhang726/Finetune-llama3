# Finetune-llama3

Meta Llama 3 was released April 2024 https://ai.meta.com/blog/meta-llama-3/. Thanks to Unsloth AI https://unsloth.ai/, it is possible to finetune Meta Llama 3 with free or cheap GPU e.g. Colab T4.

## SFT 4-bit quantized Llama 3 using GSM8K data
GSM8K is "a dataset of 8.5K high quality linguistically diverse grade school math word problems" created by OpenAI https://github.com/openai/grade-school-math. 
GSM8K Socratic Dataset is used in sft.
Taining with 1 epoch took ~ 2 hours on Colab T4.


## SFT 4-bit quantized Llama 3 using Automated Essay Scoring data 
This finetuning uses data from Automated Essay Scoring 2.0 hosted by Kaggle https://www.kaggle.com/competitions/learning-agency-lab-automated-essay-scoring-2.
Training with 1 epoch took 6+ hours on Colab T4.





