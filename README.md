# OpenFE Demo: USRSE 2025

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/OpenFreeEnergy/openfe-usrse-demo/blob/add_notebook/src/openfe_demo.ipynb)

You can find the demo notebook in `openfe_demo.ipynb`, or by clicking on the "Open in Colab" button above.

## Install 
###  with `micromamba`

```bash
micromamba create -n openfe --file openfe-conda-lock.yml
micromamba activate openfe
```

### with `conda`

```bash
conda create -n conda-lock -c conda-lock
conda activate conda-lock
conda-lock install -n openfe-demo openfe-conda-lock.yml
conda activate openfe-demo
```
