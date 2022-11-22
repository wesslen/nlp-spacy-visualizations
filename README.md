# NLP/spaCy visualization tools

## Easiest way to get started

The easiest way to run is to run it in Binder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/wesslen/nlp-spacy-visualizations/HEAD?labpath=01-spacy-visualizer.ipynb)

This way you don't have to install anything locally. It may take 5-10 minutes to start so be patient. Also, the `bulk` example at the bottom won't work because it requires opening up a new port.

## ⏩ Getting started

It is highly recommended to create a new virtual environment before starting. I only installed this with Python 3.9 so it may not work for different Python versions.

```bash
python3.9 -m venv .env
source .env/bin/activate
```

When you have a fresh environment, run the following commands from the root repo directory:

```bash
pip install --upgrade pip
pip install -r requirements.txt
```
## To start Jupyter

To start Jupyter, run:

```bash
jupyter-lab
```