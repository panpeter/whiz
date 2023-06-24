# Whiz

This Python script allows users to integrate a Q&A chatbot into their project. The chatbot leverages the power of OpenAI's ChatGPT to answer questions related to the project. It uses the LangChain library for text processing and retrieval.

## Features

- Interactive Q&A: Users can ask questions and receive answers related to their project.
- Intelligent Answering: The chatbot utilizes OpenAI's ChatGPT model to provide informative and context-aware responses.
- Project Data Caching: The script caches project data to enhance search and retrieval speed.

## Prerequisites

Before running the script, ensure you have the following:

- Python 3.x installed on your system.
- An OpenAI API key. Sign up on the [OpenAI website](https://openai.com/) to obtain an API key.

## Installation

1. Clone or download the project files to your local machine.

2. Install the required dependencies by running the following command:

```bash
pip install -r requirements.txt
```

3. Set your OpenAI API key as an environment variable:

```bash
export OPENAI_API_KEY="your-openai-api-key"
```

## Usage

1. Place the script in your project directory.

2. Open a terminal or command prompt and navigate to your project directory.

3. Run the script using the following command:

```bash
python whiz.py
```

4. The chatbot will start running and wait for your questions. Type your questions and press Enter to receive the chatbot's responses. To exit the chatbot, type "exit" and press Enter.

## Customization

- File Extensions: By default, the script searches for project files with popular extensions such as `.py`, `.html`, `.css`, etc. If you want to include or exclude specific file extensions, modify the `file_extensions` list in the script.

- Search Parameters: The script uses default search parameters for retrieval, such as the distance metric, fetch limit, and relevance. If you want to customize these parameters, modify the `retriever.search_kwargs` dictionary in the script.

- Language Model: The script utilizes the OpenAI ChatGPT model for answering questions. If you want to use a different model or experiment with other language models, you can modify the `model` variable in the script.

## Acknowledgments

- [OpenAI](https://openai.com/) for their powerful language models and APIs.
- [LangChain](https://github.com/langchain/langchain) for providing text processing and retrieval capabilities.
- [GitPython](https://gitpython.readthedocs.io/) for Git integration in Python.

## Contact

For any questions or suggestions, please feel free to reach out to [piotrwilczek@gmail.com](mailto:piotrwilczek@gmail.com).