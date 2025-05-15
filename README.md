# C-QuEE: Cole's Quantum Efficiency Equation

**Author:** Gabriel E.K. Cole  
**Affiliation:** NeurQL (Founder)  
**Email:** gabrielcolehi@gmail.com  

**C-QuEE** (Cole’s Quantum Efficiency Equation) is a tunable, modular metric for evaluating the real-world software efficiency of quantum algorithms. Unlike hardware-bound metrics such as Quantum Volume or CLOPS, C-QuEE evaluates performance from a software-centric perspective, applicable to both real and simulated quantum environments.

---

## Metric Overview

C-QuEE evaluates quantum software across four dimensions:

| Penalty Type            | Description                                               |
|-------------------------|-----------------------------------------------------------|
| **Noise Penalty**       | Penalizes low fidelity and quantum noise                  |
| **Memory Penalty**      | Measures inefficient qubit utilization                    |
| **Time Penalty**        | Compares quantum versus classical runtime                 |
| **Scalability Penalty** | Assesses input size impact on qubit growth                |

**Formula:**

C-QuEE =  
1 - 
(α × Avg(NoisePenalty) +  
 β × Avg(MemoryPenalty) +  
 γ × Avg(TimePenalty) +  
 δ × Avg(ScalabilityPenalty))

The output is a score from **0 (worst)** to **1 (optimal)**.

## Whitepaper

A complete explanation of the metric, including methodology and a worked example, is available in the whitepaper:  
[C-QuEE_Whitepaper_v1.pdf](./C-QuEE_Whitepaper_v1.pdf)

---

## Development

C-QuEE is being actively developed as part of an open-source benchmarking suite that includes:

- Automated scoring from real or simulated test cases
- Visualization tools for penalty breakdown
- Platform-agnostic comparisons (e.g., Qiskit, Cirq, PennyLane)
- Future extension to **C-QuEE-C**, a classical comparison variant

---

## Research Context

C-QuEE was developed by **Gabriel E.K. Cole**, an undergraduate researcher at **Oregon State University**, majoring in:

- Computer Science (Artificial Intelligence)
- Biological Data Science (Computational Biology)
- Minor in Music Performance

The project is part of **NeurQL**, a research initiative founded by the author that focuses on quantum software, AI, and genomics. At 18, Gabriel is leading the development of open benchmarking tools to support scalable and accessible quantum computing research.

---

## License

This project is licensed under the MIT License.  
See [LICENSE](./LICENSE) for full terms.

---

## Contact

For questions, collaboration inquiries, or contributions, please contact:  
**gabrielcolehi@gmail.com**
