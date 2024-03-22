# Fine-Tuning LLMs

*View these notebooks in a more readable format at [danliden.com/fine-tuning](https://danliden.com/fine-tuning).*

This series of notebooks is intended to show how to fine-tune language models, starting from smaller models on single-node single-GPU setups and gradually scaling up to multi-GPU and multi-node configurations.

Existing examples and learning resources generally do not bridge the practical gap between single-node single-GPU training when all parameters fit in VRAM, and the various forms of distributed training. These examples, when complete, are intended to show how to train smaller models given sufficient compute resources and then scale the models up until we encounter compute and/or memory constraints. We will then introduce various distributed training approaches aimed at overcoming these issues.

This will, hopefully, serve as a practical and conceptual bridge from single-node single-GPU training to distributed training with tools such as deepspeed and FSDP.

## How to use this repository

The examples in this repository are intended to be read sequentially. Later examples build on earlier examples and gradually add scale and complexity.

## Contributing

Contributions are welcome, and there are a few different ways to get involved.
- If you see an error or bug, please [open an issue](https://github.com/djliden/fine-tuning/issues/new) or open a PR.
- If you have a question about this repository, or you want to request a specific example, please [open an issue](https://github.com/djliden/fine-tuning/issues/new).
- If you're interested in contributing an example, I encourage you to get in touch. You can [open an issue](https://github.com/djliden/fine-tuning/issues/new) or reach out by email or social media.