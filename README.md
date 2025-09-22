# OpenFE Demo: USRSE 2025

## Install 


### installing with `micromamba`

```bash
micromamba create -n openfe --file openfe-conda-lock.yml
micromamba activate openfe
```

### installing with `conda`

```bash
conda create -n conda-lock -c conda-lock
conda activate conda-lock
conda-lock install -n openfe-demo openfe-conda-lock.yml
conda activate openfe-demo
```

### running with google colab

[Click here to run in google colab](https://colab.research.google.com/github/OpenFreeEnergy/openfe-usrse-demo/blob/add_notebook/src/openfe_demo.ipynb)