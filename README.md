
## Contexte
This project aims to read numbers from images using the MNIST dataset (MNIST.ipynb), and classify the subcellular localizations from protein sequences using the Multiloc dataset. 

## Installation
### Clone the git repository:
 ```bash
git clone git@github.com:StudiousPillow/projet_cours_MNIST.git
```
### Install the environment
#### With conda
You can use the environment.yml to install the conda environment :
```bash
conda env create -f environment.yml
```
Then activate it:
```bash
conda activate projet_cours_MNIST
```

### With pixi
You can also use [pixi](https://pixi.sh/).
First, install pixi (for linux and macOS, for windows see(https://pixi.sh/latest/#installation)):
```bash
curl -fsSL https://pixi.sh/install.sh | bash
```
Then install the environment (it will create a local .pixi/ and pixi.lock from the pixi.toml):
```bash
pixi install
```

## Usage
You can then execute the jupyter notebooks from your preffered interface.


