# Advent of Code 2022

A collection of Jupyter notebooks providing solutions to the daily challenges as set by the [Advent of Code 2022](https://adventofcode.com)

## Quick Start
### Linux
#### Install Miniconda

```
cd ~
wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh
chmod +x Miniconda3-latest-Linux-x86_64.sh
./Miniconda3-latest-Linux-x86_64.sh
```

#### Update Conda
```
conda update -n base -c defaults conda
```

#### Clone this Repository
```
git clone git@github.com:dominicfriend/aoc2022.git
```

#### Create and Activate a Virtual Environment
```
cd aoc2022
conda env create --f environment.yaml
conda activate aoc
```

#### Start a Jupyter Notebook Server
```
jupyter notebook
```
