# LoRA
LoRA: Low-Rank Adaptation of Large Language Models 

Note:
- Added [LORD: Low Rank Decomposition Of Monolingual Code LLMs For One-Shot Compression](http://arxiv.org/abs/2309.14021) in `lora_decompose()`
- [VeRA: Vector-based Random Matrix Adaptation](https://arxiv.org/abs/2310.11454) does not work well when using their suggested initialization strategies, search for variable `FOLLOW_INIT_STRATEGIES` in the code, and VeRA also can only be applied every 3 layers instead of every 2 layers of gpt-neoX model, without significant eyeball inference/test performance drop.

TODO:
- MoLoRA (Mixture of Experts for LoRA)

Credit: AI chatbot, [@Ayush Kaushal](https://github.com/Ayushk4), [@ontocord](https://github.com/ontocord/) , [@cloneofsimo](https://github.com/cloneofsimo/)
