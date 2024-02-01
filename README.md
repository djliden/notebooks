# Fine-Tuning LLMs

This series of notebooks is intended to show how to fine-tune language models, starting from smaller models on single-node single-GPU setups and gradually scaling up to multi-GPU and multi-node configurations.

Existing examples and learning resources generally do not bridge the practical gap between single-node single-GPU training when all parameters fit in VRAM, and the various forms of distributed training. These examples, when complete, are intended to show how to train smaller models given sufficient compute resources and then scale the models up until we encounter compute and/or memory constraints. We will then introduce various distributed training approaches aimed at overcoming these issues.

This will, hopefully, serve as a practical and conceptual bridge from single-node single-GPU training to distributed training with tools such as deepspeed and FSDP.

## How to use this repository

The examples in this repository are intended to be read sequentially. Later examples build on earlier examples and gradually add scale and complexity.

## Contents
[1. Fine-Tune T5-Small on Single GPU](./1_t5_small_single_gpu/1.%20T5-Small%20on%20Single%20GPU.ipynb)

[2. Fine-Tune GPT-2 on a Single GPU](./2_gpt2_single_gpu/2.%20GPT2%20on%20a%20single%20GPU.ipynb)

[3. Instruction tuning TinyLlama](./3_tinyllama_instruction_tune/3.%20instruction%20tuning%20tinyllama%20on%20a%20single%20GPU.ipynb)