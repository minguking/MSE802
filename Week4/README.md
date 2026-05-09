# Quantum Computing Tasks

A collection of introductory quantum computing exercises using **Qiskit**.

---

## Tasks

### Task 1 — 2-Qubit Circuit with 90° Phase Shift
Creates a 2-qubit circuit using `H` gates for superposition and `S` gates for a 90° phase shift. The resulting quantum state is visualized using a **Q-sphere**.

### Task 2 — OpenQASM Circuit Import
Defines a Bell state circuit in **OpenQASM 2.0** format, imports it into Qiskit, and runs it on the `AerSimulator`. Results are displayed as a histogram.

### Task 3 — Density Matrix: Diagonal and Off-Diagonal Elements
Computes the **density matrix** of a 2-qubit superposition state. Diagonal elements represent measurement probabilities; off-diagonal elements represent quantum coherence. Visualized as a **3D bar chart** showing real and imaginary amplitudes.

### Task 4 — Random Circuit
Generates a random 2-qubit circuit using Qiskit's built-in `random_circuit()`. Drawn using `draw(output='mpl')` — no dump method used. Each qubit's state is visualized on a **Bloch sphere**.
