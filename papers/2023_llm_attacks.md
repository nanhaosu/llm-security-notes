# Universal and Transferable Adversarial Attacks on Aligned Language Models


## Basic Information

Title:
Universal and Transferable Adversarial Attacks on Aligned Language Models

Authors:
Andy Zou, Zifan Wang, Nicholas Carlini, J. Zico Kolter, Matt Fredrikson

Year:
2023

Area:
LLM Security / AI Safety / Adversarial Machine Learning


## Motivation

Large Language Models are increasingly aligned to avoid generating harmful content.

However, alignment methods may still be vulnerable to jailbreak attacks.

This paper studies whether automated adversarial methods can bypass safety alignment.


## Problem

How can we automatically generate jailbreak prompts that transfer across different language models?


## Key Idea

The paper proposes an automated method to find adversarial suffixes.

These suffixes are appended to user prompts and optimized to increase the probability that the model produces an unsafe response.


## Method

Main components:

- Gradient-based optimization
- Adversarial suffix generation
- Transfer attacks across models


## Experiments

Models evaluated:

- Vicuna
- LLaMA-based models
- Closed-source chatbots


Metrics:

- Attack Success Rate (ASR)


## My Understanding

(Write your own understanding here)


## Research Questions

Possible future directions:

- How can we design stronger defenses?
- How can we evaluate LLM safety more reliably?
- Can we build adaptive defense mechanisms?
