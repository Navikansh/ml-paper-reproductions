# ML Paper Reproductions

This repository contains my implementations and experimental analyses
of influential machine learning research papers.

The goal is to deeply understand modern ML architectures by reproducing
their results and studying their behavior in practice.

---

## Implemented Papers

### 1. Matrix Factorization for Recommender Systems

Paper:
Yehuda Koren, Robert Bell, Chris Volinsky — *Matrix Factorization Techniques for Recommender Systems*

Implementation:
- Implemented collaborative filtering using matrix factorization
- Trained model using stochastic gradient descent
- Evaluated recommendation performance using RMSE

Key insights:
- Latent factors capture user preferences effectively
- Model performance improves with regularization tuning

---

### 2. Deep Residual Learning for Image Recognition (ResNet)

Paper:
Kaiming He et al. — *Deep Residual Learning for Image Recognition*

Implementation:
- Implemented residual blocks in PyTorch
- Trained simplified ResNet architecture
- Studied degradation problem in deep networks

Experiments:
- Compared plain CNN vs residual architecture
- Analyzed training stability and convergence

---

## Future Implementations

- Attention Is All You Need (Transformer)
- BERT: Pre-training of Deep Bidirectional Transformers
- Neural Collaborative Filtering
