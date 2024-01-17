# Natural-Language-Inference

Internal mechanisms of an autoregressive transformer language model, GPT-2, will be probed. Neural networks such as transformers have a reputation for being black boxes.
However, they are far from being so. Here, we built intuition into how the structure and
internal states of such a transformer reveal its behavior during generation. In particular, we examined the question, do language models “know” when they’ve said something contradictory?
Here, to do this, you will be “probing” models with classifiers, a conceptual tool to better
understand the dynamics inside a neural network.

# 4 Steps:

1. Preparation (SNLI dataset)

2. Obtain Internal States using TraceDict (20 points)

3. Train a classifer

4. Probe MLP and attention layers

5. Other exploratory tasks