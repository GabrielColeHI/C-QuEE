# C-QuEE: Cole's Quantum Efficiency Equation

**Author:** Gabriel E.K. Cole  
**Affiliation:** NeurQL (Founder)  
**Email:** gabrielcolehi@gmail.com  

**C-QuEE** (Cole’s Quantum Efficiency Equation) is a tunable, modular metric for evaluating the *real-world software efficiency* of quantum algorithms. Unlike hardware-bound metrics like **Quantum Volume** or **CLOPS**, C-QuEE evaluates performance from a software-centric perspective, applicable to both real and simulated quantum environments.

---

## 📐 Metric Overview

C-QuEE evaluates quantum software across four dimensions:

| Penalty Type         | Description                                              |
|----------------------|----------------------------------------------------------|
| **Noise Penalty**     | Penalizes low fidelity and quantum noise                |
| **Memory Penalty**    | Measures inefficient qubit utilization                  |
| **Time Penalty**      | Compares quantum vs classical runtime                   |
| **Scalability Penalty** | Assesses input size impact on qubit growth             |

**Formula:**

\[
\text{C-QuEE} = 1 - \left( \alpha \cdot \text{NoisePenalty} + \beta \cdot \text{MemoryPenalty} + \gamma \cdot \text{TimePenalty} + \delta \cdot \text{ScalabilityPenalty} \right)
\]

The metric outputs a score from **0 (worst)** to **1 (optimal)**.

---

## 📄 Whitepaper

A complete explanation of the metric, including methodology and a worked example, is available in the whitepaper:  
👉 [C-QuEE_Whitepaper_v1.pdf](./C-QuEE_Whitepaper_v1.pdf)

---

## 🛠️ Current Development

C-QuEE is being actively developed as part of an open-source benchmarking suite that includes:

- Automated scoring from real/simulated test cases
- Visualization tools for penalty breakdown
- Platform-agnostic comparisons (e.g., Qiskit, Cirq, Pennylane)
- Future extension to **C-QuEE-C**: Classical comparison variant

---

## 🔬 Research Context

Developed by **Gabriel E.K. Cole**, an undergraduate researcher at **Oregon State University**, majoring in:

- Computer Science (Artificial Intelligence focus)  
- Biological Data Science (Computational Biology option)  
- Minor in Music Performance  

Gabriel founded **NeurQL**, a research initiative focused on the intersection of **quantum software**, **AI**, and **genomics**.  
At age 18, he is leading the development of public tools to benchmark and improve quantum computing accessibility and transparency.

---

## ⚖️ License

This project is licensed under the MIT License.  
See [LICENSE](./LICENSE) for full terms.

---

## 📬 Contact

For contributions, collaboration, or questions, reach out:  
📧 **gabrielcolehi@gmail.com**
