# LoRA Rank and Scale Exploration

This repository explores whether it's appropriate to extend LoRA's rank and scale parameters into learnable vectors.

## Background

LoRA (Low-Rank Adaptation) typically uses fixed rank and scale values during training. This project investigates the potential benefits of making these parameters learnable on a per-layer basis.

## Key Questions

- Can making rank and scale learnable improve model performance?
- What are the computational costs and memory implications?
- How does this affect training stability?
- Are there specific architectures or tasks where this approach is more beneficial?

## Structure

- `src/`: Source code for experiments
- `outputs/`: Experimental results and analysis
- `logs/`: Training and evaluation logs
- `opencompass/`: OpenCompass evaluation framework and configurations

## Usage

[To be added]

## References

- Original LoRA paper: [LoRA: Low-Rank Adaptation of Large Language Models](https://arxiv.org/abs/2106.09685)
- rsLoRA [A Rank Stabilization Scaling Factor for Fine-Tuning with LoRA](https://arxiv.org/abs/2312.03732)