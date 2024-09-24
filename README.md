# MLP from scratch in Numpy

----------

This repo contains code for creating an MLP using only numpy. Both forward and backward passes are implemented from scratch.

A 2 layer test MLP is trained on the MNIST dataset with 97.2% accuracy on the test set. For now the code can be found in `src/mlp_numpy/exploration.ipynb`. 

----------

To run the repo/notebook, download [uv](https://docs.astral.sh/uv/) and run the following command:

```bash
uv venv
source .venv/bin/activate # .venv\Scripts\activate on Win
uv sync
```