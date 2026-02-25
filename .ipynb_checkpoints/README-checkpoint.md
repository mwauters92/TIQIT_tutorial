# TIQIT_tutorial
Python notebook with simple examples of quantum information processing with the qiskit package

# Introduction to Quantum Circuits with Qiskit

Welcome to the Quantum Computing Notebook! This notebook serves as an introduction to quantum circuit concepts using the Qiskit library. The primary goal of the hands-on sessions is to familiarize yourself with quantum circuits and learn how to create entangled states, such as the Bell States, using Qiskit. Additionally, in the second hour, we will delve into implementing a protocol (or part of it) for Quantum Teleportation.

## Installation

To run the notebook, you have two options:

1. **Local Installation:** First install anaconda or miniconda, following the instructions [here](https://www.anaconda.com/download/success). Form the anaconda prompt, you can now create a python environment and install the necessary packages. Type
```bash
conda create -n quantum_computing python=3
conda activate quantum_computing
pip install numpy scipy matplotlib qiskit
pip install jupyter
pip install qiskit[visualization]
pip install qiskit_aer
```
To deactivate the python environment type
```bash
conda deactivate
```
The activate and deactivate commands allow you to move from the default (base) environment and the ones you create.

2. **IBM Quantum Lab:**  Alternatively, use the provided [IBM Quantum Lab](https://quantum-computing.ibm.com/lab) environment. This option allows you to run the notebook in a standard browser without any local installations. All you need is a Google Account to sign in and start experimenting with quantum circuits.
   - Download the Hands_on_01.ipynb notebook.
   - Log in in IBM Quantum Lab and upload the notebook.

## Hands-on Sessions

The first hour will focus on understanding and creating entangled states, particularly the Bell States, using Qiskit. These sessions will guide you through the process of creating quantum circuits, applying gates, and measuring qubits to observe entanglement phenomena.

In the second hour, we will delve into implementing a protocol for Quantum Teleportation. This protocol is a fundamental concept in quantum information theory and demonstrates the transfer of quantum information from one qubit to another using entanglement and classical communication.

## Contents

- **Notebook Files:** [Hands_on_01.ipynb, Hands_on_02.ipynb]
- **PDF Installation Guide:** [FirstStepsWithPythonAndQiskit.pdf]()

## License

This project is licensed under the [MIT License]().

