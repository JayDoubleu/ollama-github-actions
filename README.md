# Project Name

## Description

This project uses the Ollama AI platform to interact with the gemma:2b and gemma:7b models. The interactions are scripted in Python and executed in a GitHub Actions workflow.

## Setup

1. Install Python 3.11 or later.
2. Install the Ollama Python bindings with `python3 -m pip install ollama`.
3. Pull the gemma:2b and gemma:7b models from the Ollama registry with `ollama pull gemma:2b` and `ollama pull gemma:7b`.

## Usage

Run the scripts `run_gemma2b.py` and `run_gemma7b.py` with Python 3.11 or later.

## GitHub Actions

This project uses a GitHub Actions workflow defined in `.github/workflows/ollama.yml`. The workflow is triggered on push and pull request events to the main branch, and can also be manually dispatched.

## License

Add license information here.

## Contact

Add contact information here.
