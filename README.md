# Question Answering with LangChain and Chroma DB
This repository contains a Jupyter notebook demonstrating how to perform question answering over documents using LangChain and Chroma DB.For a demonstration of how to perform question answering over documents using Chroma and LangChain, refer to this notebook. For utilizing a persistent database with Chroma and LangChain, consult this notebook.

## Setup
1. Install the required packages using 

```
pip install langchain langchain-openai chromadb llama-index.
```

2. Set Up Environment Variables:

To authenticate your API requests, you need to set up your environment variables for your [OpenAI](https://platform.openai.com/api-keys) and [Langchain](https://smith.langchain.com/o/62b71014-e718-5aff-a663-8a0f4862dcd7/settings) API keys. Replace "API_KEY_HERE" with your actual API keys:

```bash
OPEN_AI_API_KEY = "API_KEY_HERE"
LANGCHAIN_API_KEY = "API_KEY_HERE"
```

3. Ensure you have a text file (input.txt) with the documents you want to use for question answering.

Usage
## Example Questions
"How are democracies responding to the current global challenges, and what does this suggest about the prevailing global sentiment towards peace and security?"

