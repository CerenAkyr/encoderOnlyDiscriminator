# Encoder Only Discriminator
Data-driven global conformance checking with encoder-only discriminator architecture.
It uses encoder-only Transformer discriminator, dynamic padding with attention masking, log / anti-log training setup.

It reproduced experiments from the reference work with the above description. The experiments include:
- Experiment 1: Controlled models
- Experiment 2: Noise injection
- Experiment 3: Real-life event logs

## Reference Work:
The work is directly the extension of the log/anti-log discriminative framework introduced by Peeperkorn et al. (2023) by replacing the LSTM encoder with a self-attention-based Transformer, while preserving the original fitness and precision definitions.

Full citation: Peeperkorn, J., vanden Broucke, S., & De Weerdt, J. Global Conformance Checking Measures Using Shallow Representation and Deep Learning, Engineering Applications of Artificial Intelligence, 2023

Data is also from the same work and can be reached from here:
https://github.com/jaripeeperkorn/ML_Conformance
