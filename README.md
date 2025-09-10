# AI4Astro IMPRS 2025 - Transformer Tutorial

This repository contains materials for a transformer tutorial given at the AI for Astronomy IMPRS 2025 Summer School (https://www.imprs-hd.mpg.de/Summer-School).

## Overview

This tutorial covers the fundamentals of decoder-only transformer architectures. The materials include hands-on exercises to build understanding of attention mechanisms.

## Contents

- `tutorial_attention_imprs.ipynb` - Interactive Jupyter notebook with fill-in exercises to implement a transformer from scratch using NumPy

## Prerequisites

- Python 3+
- NumPy
- Jupyter Notebook
- Basic understanding of linear algebra and neural networks

## Getting Started

1. Clone this repository:
   ```bash
   git clone https://github.com/errai34/ai4astro_imprs_2025.git
   cd ai4astro_imprs_2025
   ```

2. Install required dependencies (if you need to!):
   ```bash
   pip install numpy jupyter matplotlib
   ```

3. Start Jupyter notebook:
   ```bash
   jupyter notebook
   ```

4. Open `tutorial_attention_imprs.ipynb` and follow the exercises

## Tutorial Structure

The tutorial is designed to be hands-on and interactive, covering:

- Attention mechanisms and self-attention
- Multi-head attention
- Positional encoding
- Complete decoder-only transformer implementation

## Learning Objectives

By the end of this tutorial, participants will:
- Understand the core concepts behind decoder-only transformer architectures
- Implement attention mechanisms from scratch
- Build a decoder-only transformer model using only NumPy
- Appreciate the power and flexibility of attention-based models for sequence processing

## Resources

- [Attention Is All You Need](https://arxiv.org/abs/1706.03762) - Original transformer paper
- [Transformer Circuits](https://transformer-circuits.pub/2021/framework/index.html) - A mechanistic interpretability approach to understanding transformers
- [The Illustrated Transformer](http://jalammar.github.io/illustrated-transformer/) - Visual guide to transformers
- [An ever more Illustrated Transformer](https://pi-tau.github.io/posts/transformer/#token-embedding-layer/) - Super intuitive explanations
- [Transformers from Scratch](https://peterbloem.nl/blog/transformers) - Detailed implementation guide


## Contributing

If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## License

This educational material is provided under the MIT License.
