# C-QuEE: Cole's Quantum Efficiency Equation

**Author:** Gabriel E.K. Cole  
**Affiliation:** NeurQL (Founder)  
**Email:** gabrielcolehi@gmail.com  

**C-QuEE** is a tunable, modular metric for evaluating the real-world efficiency of quantum software. Unlike hardware-bound metrics such as Quantum Volume or CLOPS, C-QuEE focuses on how quantum algorithms perform across real or simulated quantum systems from a software perspective.

It evaluates four dimensions:

- **Noise Penalty** – based on fidelity loss  
- **Memory Penalty** – based on qubit utilization  
- **Time Penalty** – based on quantum vs classical runtime  
- **Scalability Penalty** – based on input size vs qubit growth  

---

## Whitepaper

Download the full whitepaper for methodology, definitions, and a worked example:  
[C-QuEE_Whitepaper_v1.pdf](./C-QuEE_Whitepaper_v1.pdf)

---

## Development

This metric is currently being implemented as part of a benchmarking tool that includes:

- Automated score calculation from test case input
- Visualization of penalty components
- Platform-agnostic architecture for comparing across quantum backends
- Extension to **C-QuEE-C**, a companion metric for comparing quantum vs classical performance

---

## Research Background

C-QuEE was developed by **Gabriel E.K. Cole**, an undergraduate researcher at Oregon State University studying **Computer Science (Artificial Intelligence)** and **Biological Data Science (Computational Biology)**. The project was conducted under **NeurQL**, a research and development initiative founded by the author focused on quantum software, AI, and genomics.

At 18 years old, Gabriel is leading the development of open-source benchmarking tools to support transparent, accessible, and scalable quantum software research at NeurQL.

---

## License

This project is licensed under the MIT License. See [LICENSE](./LICENSE) for details.

---

## Contact

For questions, contributions, or collaboration inquiries, please reach out:

**gabrielcolehi@gmail.com**
