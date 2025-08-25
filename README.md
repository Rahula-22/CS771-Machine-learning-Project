# CS771-Machine-learning-Project
Implementation of Multi-level PUF (ML-PUF) security analysis and delay recovery for Arbiter PUFs. The project demonstrates that ML-PUFs can still be modeled using linear learning techniques and implements algorithms to reconstruct feasible delay parameters from underdetermined Arbiter PUF models.

# Problem Statement 
Problem Statement

This project addresses two key challenges in hardware security:

1. Multi-level PUF (ML-PUF) Security Analysis – ML-PUF is a variant of arbiter PUF designed to resist machine learning attacks. The task is to prove that linear models can still accurately predict ML-PUF responses by generating appropriate feature vectors from challenge-response pairs.

2. Delay Recovery in Arbiter PUFs – Given a linear model representation of an Arbiter PUF, recover a valid set of non-negative delays 
( 𝑝𝑖,𝑞𝑖,𝑟𝑖,𝑠𝑖) that generate the same model, despite underdetermined constraints.

# Objective 
Analyze and model ML-PUF challenge-response behavior using linear learning techniques.

Demonstrate that ML-PUF responses are still predictable despite added complexity.

Implement algorithms to recover feasible delay parameters from given linear models for 64-bit Arbiter PUFs.

# Datasets
ML-PUF: 8-bit challenges with corresponding 1-bit responses (6400 train CRPs, 1600 test CRPs).

Arbiter PUF: 10 linear models, each with a 64-dimensional weight vector and a bias term.
