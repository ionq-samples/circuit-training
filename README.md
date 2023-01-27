# Generative Learning Using a Quantum Computer
In this tutorial, we implement Data-driven quantum circuit learning (DDQCL), based on the 2019 paper Training of quantum circuits on a hybrid quantum computer by Zhu et. al, using the Qiskit SDK.

# DQCCL
DDQCL is a hybrid quantum-classical technique for generative modeling of classical data, using a parametrized quantum circuit as the model being trained. Training occurs by sampling the output of a parametrized circuit run on a quantum computer and updating the circuit parameters using classical optimization techniques. Convergence produces a circuit that captures the correlations in the training data, thus serving as a generative model for the data itself.

See: `circuit-training.ipynb` for more information.

Prerequisites
 - Qiskit
 - IonQ provider for Qiskit
 - matplotlib
