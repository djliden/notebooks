# Jupyter Notebook Examples

*View these notebooks in a more readable format at [danliden.com/notebooks](https://danliden.com/notebooks).*

This repository contains a collection of Jupyter notebooks demonstrating various concepts and techniques across different fields. Currently, it includes a series on fine-tuning language models, but it will expand to cover other topics in the future.

## Fine-Tuning LLMs

The fine-tuning section shows how to fine-tune language models, starting from smaller models on single-node single-GPU setups and gradually scaling up to multi-GPU and multi-node configurations.

Existing examples and learning resources generally do not bridge the practical gap between single-node single-GPU training when all parameters fit in VRAM, and the various forms of distributed training. These examples, when complete, are intended to show how to train smaller models given sufficient compute resources and then scale the models up until we encounter compute and/or memory constraints. We will then introduce various distributed training approaches aimed at overcoming these issues.

This will, hopefully, serve as a practical and conceptual bridge from single-node single-GPU training to distributed training with tools such as deepspeed and FSDP.

## How to use this repository

The examples in this repository are organized by topic. Within each topic, the notebooks are intended to be read sequentially. Later examples often build on earlier examples and gradually add complexity.

## Contributing

Contributions are welcome, and there are a few different ways to get involved.
- If you see an error or bug, please [open an issue](https://github.com/djliden/notebooks/issues/new) or open a PR.
- If you have a question about this repository, or you want to request a specific example, please [open an issue](https://github.com/djliden/notebooks/issues/new).
- If you're interested in contributing an example, I encourage you to get in touch. You can [open an issue](https://github.com/djliden/notebooks/issues/new) or reach out by email or social media.