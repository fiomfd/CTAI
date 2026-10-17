# CTAI
This repository presents a framework integrating generative AI into interactive computational notebooks—specifically Pluto for Julia and Jupyter for Python—to foster mathematical and computational thinking in vector geometry and linear algebra. Addressing secondary to early undergraduate curricula in Singapore, the system enables learners to actively explore basic concepts—such as 3D lines and planes, linear mapping, and singular value decomposition and the Haar wavelet decomposition—through real-time parameter manipulation using reactive UI widgets. The system also provides calculating exercises and solutions on matrix operations, row echelon forms, determinants, and inverse matrices. Some solutions are created by generative AI.  To overcome the hallucination and opacity risks of generative AI in STEM education, our environment pairs an LLM-based problem-and-solution generator with a deterministic computer algebra backend that automatically verifies AI outputs. 

- ai-pluto.jl: Pluto for Julia on computers

- ai-jupyter.ipynb: Jupyter Notebook for Python on computers

- ai-colab.ipynb: Jupyter Notebook for Python on the Google Colab

    [![Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/fiomfd/CTAI/)
