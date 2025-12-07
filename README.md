# Enable-Based Bidirectional Quantum Teleportation

[![DOI](https://img.shields.io/badge/DOI-10.1007%2Fs11082--023--05351--1-blue)](https://link.springer.com/article/10.1007/s11082-023-05351-1)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com)
[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/)
[![Qiskit](https://img.shields.io/badge/Qiskit-0.44-6929C4)](https://qiskit.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Overview

This repository contains the Qiskit implementation for the paper **"Enhancing quantum teleportation: an enable-based protocol exploiting distributed quantum gates"**, published in *Optical and Quantum Electronics*.

We introduce a novel **bidirectional teleportation protocol** that significantly reduces quantum resource overhead. Traditional bidirectional protocols require two entangled pairs (4 qubits). Our enable-based approach utilizes distributed quantum gates to achieve the same functionality using only a **single two-qubit entangled state**, controlled by enabling qubits.

### Key Innovations
* **Resource Efficiency:** Achieves bidirectional teleportation with only **2 entangled qubits** (vs. 4 in standard protocols).
* **Enable-Based Control:** Uses control qubits to dynamically switch the direction of teleportation (Alice $\to$ Bob or Bob $\to$ Alice).
* **Simplified Measurements:** Relies on standard Z-basis measurements to trigger the necessary unitary corrections.
* **Distributed Gates:** Leverages Toffoli-based distributed logic for channel management.

## Getting Started

### Prerequisites
The simulation is built using **Qiskit**.

### Installation
To install dependencies:
```bash
pip install -r requirements.txt

```

## Citation
url = {[https://link.springer.com/article/10.1007/s11082-023-05351-1](https://link.springer.com/article/10.1007/s11082-023-05351-1)}
