# Quantum Computing with ATOS QLM

This repository contains code and experiments developed for the **ATOS Quantum Learning Machine (QLM)** using Python and the **myQLM** software stack by **Eviden**. The goal is to explore and simulate quantum algorithms in a versatile and hardware-agnostic environment.

## Overview

**myQLM** is a full-featured quantum software development kit that allows users to:
- Write quantum programs using **gate-based**, **analog**, or **quantum annealing** paradigms
- Simulate and optimize circuits on classical hardware
- Execute programs on real quantum processors (via QPU interfaces)
- Use advanced tools tailored for **NISQ** devices, such as **VQE**, **QAOA**, and more

This repository serves as a sandbox for building, testing, and running quantum algorithms designed for the QLM platform.

## Repository Structure

The repository is structured as follows:

├── algorithms/ # Quantum algorithms (e.g., VQE, QAOA, Grover's)
├── circuits/ # Custom and textbook quantum circuits
├── simulators/ # Tools and scripts for simulation backends
├── qpu_interface/ # Scripts for connecting with actual quantum hardware
├── utils/ # Helper functions and utilities
└── README.md # Project documentation

## Getting Started

### Prerequisites

- Python 3.8+
- [myQLM](https://myqlm.github.io) (installed locally or on the ATOS QLM)

### Installation

To get started with this repository, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/qlm-project.git
   cd qlm-project

2. Install the dependencies:
pip install -r requirements.txt

4. [Optional] Set up myQLM:
Refer to the official installation guide for detailed instructions on installing and configuring myQLM.



## Connecting to a Quantum Processor
This repository contains templates for connecting to Quantum Processing Units (QPUs) via myQLM's extensible plugin system. To connect to a QPU, you will need:

* Access credentials from a quantum provider (e.g., ATOS, IBM, etc.)

* The correct configuration for connecting to the QPU

Refer to the qpu_interface/ directory for specific setup instructions and code examples.

## License
This project is licensed under the GNU General Public License v3.0 - see the LICENSE file for details.

## Contributing
Contributions are welcome! If you encounter bugs or have ideas for improvements, feel free to open an issue or submit a pull request.

### Acknowledgements
- Thanks to Eviden for developing the myQLM software stack.

- Special thanks to the open-source community for contributing to quantum software advancements.

