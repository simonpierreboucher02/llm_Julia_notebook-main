# LLM Julia Notebook

[![GitHub stars](https://img.shields.io/github/stars/simonpierreboucher02/llm_Julia_notebook-main?style=social)](https://github.com/simonpierreboucher02/llm_Julia_notebook-main/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/simonpierreboucher02/llm_Julia_notebook-main?style=social)](https://github.com/simonpierreboucher02/llm_Julia_notebook-main/network/members)
[![GitHub issues](https://img.shields.io/github/issues/simonpierreboucher02/llm_Julia_notebook-main)](https://github.com/simonpierreboucher02/llm_Julia_notebook-main/issues)
[![GitHub license](https://img.shields.io/github/license/simonpierreboucher02/llm_Julia_notebook-main)](https://github.com/simonpierreboucher02/llm_Julia_notebook-main/blob/main/LICENSE)
[![Julia](https://img.shields.io/badge/Julia-1.5+-purple.svg)](https://julialang.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![LLM APIs](https://img.shields.io/badge/LLM%20APIs-4%20Providers-blue.svg)](https://github.com/simonpierreboucher02/llm_Julia_notebook-main)

[![Repository Size](https://img.shields.io/github/repo-size/simonpierreboucher02/llm_Julia_notebook-main)](https://github.com/simonpierreboucher02/llm_Julia_notebook-main)
[![Last Commit](https://img.shields.io/github/last-commit/simonpierreboucher02/llm_Julia_notebook-main)](https://github.com/simonpierreboucher02/llm_Julia_notebook-main/commits/main)
[![Code Lines](https://img.shields.io/tokei/lines/github/simonpierreboucher02/llm_Julia_notebook-main)](https://github.com/simonpierreboucher02/llm_Julia_notebook-main)

This repository provides Jupyter notebooks for accessing and interacting with various Large Language Model (LLM) APIs using the Julia programming language. It demonstrates how to connect to and utilize **Anthropic**, **Cohere**, **Mistral**, and **OpenAI** APIs in Julia, allowing for experimentation with tasks like text generation, retrieval, and conversation.

## 🚀 Features

- **Multi-API Support**: Connect to 4 major LLM providers
- **Julia Integration**: Native Julia implementation for high performance
- **Jupyter Notebooks**: Interactive examples and tutorials
- **Ready-to-Use**: Complete setup instructions and dependencies
- **Cross-Platform**: Works on Windows, macOS, and Linux

## 📁 Repository Structure

- **[JULIA_ANTHROPIC_API.ipynb](https://github.com/simonpierreboucher02/llm_Julia_notebook-main/blob/main/JULIA_ANTHROPIC_API.ipynb)**: A notebook showing how to connect with Anthropic's API using Julia, including API setup, parameter tuning, and sample API requests.
- **[JULIA_COHERE_API.ipynb](https://github.com/simonpierreboucher02/llm_Julia_notebook-main/blob/main/JULIA_COHERE_API.ipynb)**: Provides guidance on using Cohere's API in Julia, with examples of text generation and retrieval tasks.
- **[JULIA_MISTRAL_API.ipynb](https://github.com/simonpierreboucher02/llm_Julia_notebook-main/blob/main/JULIA_MISTRAL_API.ipynb)**: Explains the setup for the Mistral API in Julia, demonstrating API calls and response handling.
- **[JULIA_OPENAI_API.ipynb](https://github.com/simonpierreboucher02/llm_Julia_notebook-main/blob/main/JULIA_OPENAI_API.ipynb)**: Covers the configuration and usage of OpenAI's API in Julia, including example requests and parameter customization.

## 🛠️ Getting Started

### Prerequisites

To run these notebooks, you will need:
- **Jupyter Notebook with Julia kernel (IJulia)**
- **Julia 1.5 or newer**
- API keys for each service (Anthropic, Cohere, Mistral, OpenAI)
- Required dependencies as listed in `requirements.txt`

### Installation

1. **Clone the repository**:

   ```bash
   git clone https://github.com/simonpierreboucher02/llm_Julia_notebook-main.git
   cd llm_Julia_notebook-main
   ```

2. **Install the dependencies** for Jupyter Notebook and any Python API integrations:

   ```bash
   pip install -r requirements.txt
   ```

3. **Install Julia Packages**: Open a Julia session or include these commands at the beginning of each notebook to install necessary packages:

   ```julia
   using Pkg
   Pkg.add("HTTP")  # for API requests
   Pkg.add("JSON")  # for JSON parsing
   Pkg.add("DataFrames")  # for data manipulation if needed
   Pkg.add("PyCall")  # for Python interoperability if required
   ```

### Running the Notebooks

1. **Start Jupyter Notebook**: Launch Jupyter with the Julia kernel by running:
   ```bash
   jupyter notebook
   ```
2. **Select a Notebook**: Open the notebook for the desired API provider (Anthropic, Cohere, Mistral, or OpenAI).
3. **Follow Instructions**: Each notebook includes setup steps and examples for making API requests using Julia.

## 🎯 Use Cases

- **API Interactions**: Each notebook provides examples of API calls for generating text, performing retrieval, and other LLM functionalities.
- **Parameter Customization**: Adjust parameters such as temperature, max tokens, and prompt design to optimize model output.
- **Cross-Provider Testing**: Easily compare responses from multiple LLM providers within the Julia environment.

## 📊 Repository Metrics

- **Total Notebooks**: 4 LLM API implementations
- **Supported APIs**: Anthropic, Cohere, Mistral, OpenAI
- **Language**: Julia + Jupyter
- **License**: MIT

## 🤝 Contributing

We welcome contributions! Feel free to submit issues or pull requests to improve functionality, add features, or fix bugs.

### How to Contribute

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 📄 License

This repository is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Simon Pierre Boucher**
- GitHub: [@simonpierreboucher02](https://github.com/simonpierreboucher02)

---

⭐ **Star this repository if you find it helpful!**
