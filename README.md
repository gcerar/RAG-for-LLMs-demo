# Retrieval Augmented Generation (RAG) Demo for Large Language Models (LLMs)

## Overview
This repository contains a demonstration of Retrieval Augmented Generation (RAG) applied to Large Language Models (LLMs), showcasing how incorporating external knowledge bases during the generation process can significantly enhance the model's responses. The project is initially presented in a Jupyter Notebook for easy understanding and interaction. Future updates aim to evolve this demo into a more interactive experience using Streamlit, alongside integration with an external llama.cpp server to address cold start times.

## Features
- **Jupyter Notebook Demo:** A comprehensive guide and demonstration of RAG for LLMs.

## Getting Started
### Prerequisites
Before you begin, ensure you have the following installed:
- Conda package manager

### Installation
1. Clone this repository to your local machine
2. Navigate to the cloned directory
3. Install the required dependencies: `conda env update --file environment.yaml`

### Running the Demo
1. Activate conda environment: `conda activate rag`
2. Start Jupyter Notebook or JupyterLab: `jupyter-lab`
3. Open the `EEML2024-demo.ipynb` notebook.

3. Follow the instructions within the notebook to explore the capabilities of RAG for LLMs.

## Future Plans
- **Streamlit Application:** Convert the demo into an interactive Streamlit application for a more user-friendly experience.
- **llama-cpp Server Integration:** Implement the llama-cpp server to address the model's cold start time, enhancing the overall performance.


## License
This project is licensed under the [MIT License](LICENSE) - see the LICENSE file for details.

## Acknowledgements
- Reference implementation: [medium/@murtuza753](https://medium.com/@murtuza753/using-llama-2-0-faiss-and-langchain-for-question-answering-on-your-own-data-682241488476)
- Inspiration: [promptingguide.ai/research/rag](https://www.promptingguide.ai/research/rag)