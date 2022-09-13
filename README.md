# PP6 neural networks for tabular data

[![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PauliusU/PP6-neural-networks-for-tabular-data/blob/master/PP6-neural-networks-for-tabular-data.ipynb)
[![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](https://github.com/PauliusU/PP6-neural-networks-for-tabular-data/blob/master/LICENSE)

Practical Project 6 (PP6) for Artificial Intelligence studies to solidify basics of **neural networks for tabular data** by practicing.
Project aims to improve model from *P6 L3* based on ```Boston housing``` dataset. 

## Usage

### Automatic launch

1. To run in browser click on [![Open in Google Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/PauliusU/PP6-neural-networks-for-tabular-data/blob/master/PP6-neural-networks-for-tabular-data.ipynb) badge.
2. (Or) To launch locally on Windows just **run automatic setup script** in `Git Bash`:

```bash
bash <(curl -s https://raw.githubusercontent.com/PauliusU/PP6-neural-networks-for-tabular-data/master/setup.sh)
```

### Manual launch

1. Clone this repo:

```bash
git clone https://github.com/PauliusU/PP6-neural-networks-for-tabular-data.git
```

2. Navigate into project:

```bash
cd PP6-neural-networks-for-tabular-data/
```

3. Ensure pipenv is installed:

```bash
pip install --upgrade pipenv --user
```

4. Install dependencies:

```bash
pipenv install
```

5. Run project:

```bash
pipenv run jupyter notebook PP6-neural-networks-for-tabular-data.ipynb
```

## Requirements

- [X] Go through 6 models we have trained in this part (imdb, reuters, boston housing, etc.).
- [X] Create a separate notebook, choose an example - 1 of those 6 - and improve it.
- [X] Improve it, there are a few ways:
  - Either tune model to be more precise, accurate (dropout, batch size tunning, embeddings).
  - Either implement at least 1 TODO task written at the end of the notebook (indicate which one). 
  - Add error vs. epoch visualization, decision boundary visualization, regression line visualization. 
  - Or come up with some kind of another improvement on your own (indicate which one).
- [X] Provide a small written paragraph (5-10 sentences) of what you have improved in the notebook. 
- [X] Provide a link to the notebook (double-check the share options of the notebook) when finished for review and evaluation.
