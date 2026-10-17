# CTAI: Computational Thinking and AI-Integrated Interactive Mathematics

This repository presents a framework that integrates generative AI into interactive computational notebooks—specifically Pluto for Julia and Jupyter for Python—to foster mathematical and computational thinking in vector geometry and linear algebra. 

Tailored to secondary and early undergraduate mathematics curricula (including Singapore H2 and foundational university courses), the system enables learners to actively explore key geometric and algebraic concepts—such as 3D lines and planes, linear mappings, singular value decomposition (SVD), and Haar wavelet transforms—through real-time parameter manipulation using reactive UI widgets. 

The environment also provides automated exercises and step-by-step solutions for matrix operations, row echelon forms, determinants, and matrix inverses. To mitigate the risks of hallucination and opacity inherent to generative AI in STEM education, the framework pairs an LLM-based problem-and-solution generator with a deterministic computer algebra backend that rigorously verifies all AI-generated outputs.

### Notebooks
- `ai-pluto.jl`: Pluto notebook for Julia (local execution)
- `ai-jupyter.ipynb`: Jupyter notebook for Python (local execution)
- `ai-colab.ipynb`: Jupyter notebook configured for Google Colab
