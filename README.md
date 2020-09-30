[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/umesh-timalsina/gmso_showcase/master)
![Build and Cache Docker Image](https://github.com/umesh-timalsina/gmso_showcase/workflows/Build%20and%20Cache%20Docker%20Image/badge.svg)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
## GMSO Show Case
This repository contains a collection of interactive notebooks to showcase current features and capabilities of [gmso](https://github.com/mosdef-hub/gmso).

For further information visit the `gmso` documentation at https://gmso.mosdef.org. 

### Contents:
1. [structures.ipynb](./notebooks/structures.ipynb): Demos the core data structures and design decisions in gmso.
2. [ethane_example.ipynb](./notebooks/ethane_example.ipynb): Demos a simulation workflow using features in gmso.

## Usage
Clone this repository and create a new conda environment from the file [environment.yml](./environment.yml) and start jupyter.

```shell script
$ git clone https://github.com/umesh-timalsina/gmso_showcase && cd gmso_showcase
$ conda env create --file environment.yml
$ jupyter notebook
```

Alternatively, you can directly launch this repository in [MyBinder](https://mybinder.org/v2/gh/umesh-timalsina/gmso_showcase/master).


