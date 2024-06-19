# Ollama training with the Book of Swarm

## Setup

Download Ollama from https://ollama.com/download

```sh
curl -fsSL https://ollama.com/install.sh | sh
```

Pull the models

```sh
ollama pull llama3
ollama pull mistral
```

Install requirements (it is advised to use a virtual environment)

```sh
pip install -r requirements.txt

```

Run Jupyter Lab

```sh
jupyter lab
```
