# LangChain Definitions Generator

## LangChain
Langchain is an open-source framework that enables developers working with artificial intelligence to combine large language models like GPT-4 with external data sources.

## Ollama
Ollama allows you to run open-source large language models, such as Llama 2, locally. It bundles model weights, configuration, and data into a single package, defined by a Modelfile. It optimizes setup and configuration details, including GPU usage.

## Setup
- Download and install Ollama onto the available supported platforms (https://ollama.com/download)
- Fetch available LLM model via ollama pull <name-of-model>
    * View a list of available models via the model library
    * e.g., for Llama-7b: ollama pull llama2
- This will download the default tagged version of the model. Typically, the default points to the latest, smallest sized-parameter model.
On Mac, the models will be download to ~/.ollama/models

On Linux (or WSL), the models will be stored at /usr/share/ollama/.ollama/models

- Specify the exact version of the model of interest as such ollama pull vicuna:13b-v1.5-16k-q4_0
- To view all pulled models, use ollama list
- To chat directly with a model from the command line, use ollama run <name-of-model>
- View the Ollama documentation for more commands. Run ollama help in the terminal to see available commands too.

## Llama 2
Llama 2 is released by Meta Platforms, Inc. This model is trained on 2 trillion tokens, and by default supports a context length of 4096. Llama 2 Chat models are fine-tuned on over 1 million human annotations, and are made for chat.


