# Models

QNNs, quantum kernels, generative models, hybrid training.

1. [QNN][PQC] **Quantum Self-Attention Neural Networks for Text Classification** [@Li2022QuantumSN]
    - Proposes a hybrid quantum-classical approach to implementing self-attention layers.
    - Keys and query are computed using quantum ansatzes and before being projected to a classical representation to compute attention scores.
2. [QNNs] **A Hybrid Transformer Architecture with a Quantized Self-Attention Mechanism Applied to Molecular Generation** [@Smaldone2025HybridTransformer]
    - Develops an alternative hybrid quantum-classical approach to self-attention, where attention scores are computed by quantum circuits whereas the value matrix is implemented classically.
    - The approach reduces time complexity of the attention layer from the standard $O(n^2 d))$ to $O(n^2 \log(d))$
