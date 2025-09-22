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
