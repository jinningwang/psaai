# PSAAI

Power System AI Assistant, under development.

## Installation

A conda environment is recommended for this project, and a environment file is provided. To create the environment, run:

```bash
conda env create -f environment.yml
```

A local running [Ollama](https://ollama.com/) server is required to run the model.

## How to run

To play with the model, run:

```bash
ollama start
```

Then, run the following command to start the assistant:

```bash
python agent/agent_mistral.py
```
