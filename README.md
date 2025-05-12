# Quantum Cryptography Implementation

## Overview
This repository contains a Python implementation of quantum cryptography concepts using Qiskit, focusing on the BB84 quantum key distribution protocol and an exploration of Shor's algorithm against RSA encryption. The project demonstrates fundamental quantum computing principles and their applications in cryptography.

## Features
- Implementation of the BB84 protocol for quantum key distribution
- Simulation of eavesdropping detection in quantum channels
- Analysis of noise effects on quantum communication
- Discussion of Shor's algorithm and its implications for RSA encryption
- Comprehensive explanation of quantum computing fundamentals

## Requirements
- Python 3.x
- NumPy
- Qiskit
- Qiskit Aer

```bash
pip install numpy qiskit qiskit-aer
```

## Project Structure
The project is organized as a Jupyter notebook with the following sections:
1. **Introduction to Quantum Computing** - Overview of fundamental quantum principles
2. **Quantum Cryptography** - Introduction to quantum cryptography concepts
3. **Quantum Key Distribution** - Explanation of QKD principles
4. **BB84 Protocol Implementation** - Detailed implementation with code examples
   - Quantum Communication
   - Classical Communication
   - Eavesdropping Detection
5. **Shor's Algorithm vs RSA Encryption** - Analysis of quantum threats to classical cryptography
6. **Conclusion** - Summary of findings and limitations

## Usage
To run the notebook:
1. Clone this repository
2. Install the required dependencies
3. Launch Jupyter Notebook or Jupyter Lab
4. Open the `Computing_Project.ipynb` file

```bash
jupyter notebook Computing_Project.ipynb
```

## Key Components
- **Quantum State Preparation**: Implementation of various quantum states using Qiskit circuits
- **Basis Measurement**: Simulation of quantum measurements in different bases
- **Noise Modeling**: Incorporation of depolarizing noise to simulate real-world quantum channels
- **Security Analysis**: Detection of eavesdropping through error rate calculation

## Results
The implementation successfully demonstrates:
- Generation of secure quantum keys between two parties
- Detection of eavesdropping attempts
- Effects of quantum noise on secure communication
- Current limitations of quantum computing in breaking classical encryption

## Author
Nihal Faiz (K21004658@kcl.ac.uk)


## References
The project builds upon research and concepts from quantum information theory and cryptography, with a full bibliography available in the notebook.
