# Quantum teleportation on real quantum devices

This repository contains notebooks for running quantum teleportation protocols on real quantum hardware using the Qiskit library. This repository is part of a bachelor's thesis at the Department of Applied Mathematics at VSB - Technical University of Ostrava.

## Repository contents

* **`qubit_teleportation.ipynb`**: Implements the standard qubit teleportation protocol on a real quantum device. It utilizes the Mthree mitigation algorithm to correct measurement errors.
* **`qudit_2^n_teleportation.ipynb`**: Implements generalized qudit teleportation by mapping qudits onto multiple qubits. Therefore, it is only suitable for dimensions that are powers of 2. It also applies the Mthree algorithm for error mitigation.
* **`results/`**: A directory storing the output data from each experiment and with visual representations of the Qiskit quantum circuits.

## References

The implementations in these notebooks were guided by the official Qiskit documentation, specifically referencing the [quantum-teleportation.ipynb](https://github.com/Qiskit/documentation/blob/be3df1bd249279a6883a0c28601571f2abe38fab/learning/modules/computer-science/quantum-teleportation.ipynb) learning module.