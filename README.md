# RNAtranslator 

# Modeling protein-conditional RNA design as sequence-to-sequence natural language translation

> RNAtranslator is a generative large language model (LLM) that redefines protein-conditional RNA design by framing it as a natural language translation problem. Unlike traditional methods that require post-generation optimization, RNAtranslator directly produces binding RNA sequences for any given protein target. By learning a joint representation of protein–RNA interactions from large-scale datasets, it generates RNA sequences that exhibit natural-like properties, high novelty, and enhanced binding affinity.

---

## Authors

Sobhan Shukueian Tabrizi, Sina Barazandeh, Helya Hashemi Aghdam, A. Ercument Cicek

---

## Table of Contents 

> Warning: Please note that the RNAtranslator model is completely free for academic usage. However it is licenced for commercial usage. Please first refer to the [License](#license) section for more info.

- [Installation](#installation)
- [Features](#features)
- [File Description](#files)
- [Instructions Manual](#instructions-manual)
- [Usage Examples](#usage-examples)
- [Citations](#citations)
- [License](#license)


---


## Installation

RNAtranslator is designed to run with minimal setup. Ensure you have anaconda installed.


### Requirements

For an easy setup, use the provided RNAtranslator.yml file to create a conda environment with all the necessary dependencies:

```shell
$ conda env create --name rnatranslator -f RNAtranslator.yml
$ conda activate rnatranslator
```

The environment file includes dependencies such as PyTorch, Hugging Face Transformers, Accelerate, and WandB. Adjust package versions if you are using a different operating system (e.g., macOS).
---


## Features

- Protein-Conditional Design: Directly translates protein input into binding RNA sequences.
- Sequence-to-Sequence Framework: Uses a transformer-based architecture (T5) for natural language translation applied to RNA design.
- No Post-Generation Optimization: Eliminates the need for additional optimization steps by integrating binding affinity learning into the generation process.
- Scalability: Runs on both GPU and CPU; however, GPU acceleration significantly speeds up training and inference.


