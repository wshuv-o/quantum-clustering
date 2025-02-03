# Quantum Clustering Model for Image Clustering

## Project Description
This repository contains a novel hybrid quantum-classical model designed for **image clustering tasks**, leveraging the power of **variational quantum circuits**. The model encodes image features onto **six qubits**, computes a **quantum kernel**, and applies classical clustering techniques (like **K-means**) to group image data efficiently. The methodology aims to improve clustering accuracy in complex datasets by exploiting quantum properties.


## Key Features
- **Quantum Kernel for Image Clustering:** A kernel-based clustering approach using a 6-qubit quantum circuit.
- **Hybrid Quantum-Classical Workflow:** Combines quantum kernel computation with classical clustering methods.
- **Image Feature Encoding:** Efficient mapping of image data features onto quantum states.
- **Optimization with Classical Optimizers:** Uses COBYLA for parameter optimization.
- **Performance Evaluation:** Silhouette Score metrics are used for performance assessment.

## Dataset
The model has been tested on the **MNIST Image Dataset**, with preprocessing steps to reduce image dimensions for efficient quantum processing. However, it can be extended to other image datasets.


## Getting Started

### Prerequisites
Ensure you have the following dependencies installed:
- Python 3.8+
- Pennylane
- NumPy
- SciPy
- Matplotlib
- tqdm
- scikit-learn

Install the dependencies:
```bash
pip install -r requirements.txt
