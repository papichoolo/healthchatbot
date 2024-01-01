# healthchatbot

- Make a general physician chatbot, by fine-tuning a pre-existing LLM by using our datasets, and then making a chatbot infrastructure
- ~~TODO : AutoGPTQ Fine Tuning~~
- Stop Token list
- Implement comet ml

- What was done so far:
- LLama 7b chat hf simple training using lora(peft) config 50 steps
- used non gated version of llama 7b
- used tiny llama with 1.1b params for lightweightness
- used wandb for better logging
