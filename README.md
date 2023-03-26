[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/thomasarsouze/FSPM2023/HEAD)

# FSPM workshop 

T. Arsouze & C. Pradal & ???

# Installation

## Conda install

### Conda Installation

[Conda](https://docs.conda.io) is a package manager that can be installed on Linux, Windows, and Mac.
If you have not yet installed conda on your computer, follow these instructions:

[Conda Installation](https://conda.io/projects/conda/en/latest/user-guide/install/index.html). Follow instructions for Miniconda.

[Conda Download](https://docs.conda.io/en/latest/miniconda.html). Use the Python 3.9 based installation.

#### Install Mamba

For fastest installation, install Mamba:

    conda install mamba -c conda-forge

### Get environment.yml

The file is available in the github repository. Clone it or retrieve it.
Then, create a new conda environment:

    mamba env create -f environment.yml

### Activate the env

    conda activate fspm_training

