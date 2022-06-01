[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/umesh-timalsina/gmso_showcase/master)
![Build and Cache Docker Image](https://github.com/umesh-timalsina/gmso_showcase/workflows/Build%20and%20Cache%20Docker%20Image/badge.svg)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
## GMSO Show Case
This repository contains a collection of interactive notebooks to showcase current features and capabilities of [gmso](https://github.com/mosdef-hub/gmso).

For further information visit the `gmso` documentation at https://gmso.mosdef.org. 

### Contents:
1. [GMSO_00_Overview.ipynb](./notebooks/GMSO_00_Overview.ipynb): Brief overview about the purpose and features of GMSO.
2. [GMSO_01_Abstract_Base_Classes.ipynb](./notebook/GMSO_01_Abstract_Base_Classes.ipynb): Introduction about the `gmso.abc` module.
3. [GMSO_02_Core_Classes.ipynb](./notebook/GMSO_02_Core_Classes.ipynb): Introduction to core classes in `gmso.core`.
4. [GMSO_03_Interoperability.ipynb](./notebook/GMSO_03_Interoperability.ipynb): Interaction between GMSO and other libraries.
5. [GMSO_04_Potential_Expression_and_Units.ipynb](./notebook/GMSO_04_Potential_Expression_and_Units.ipynb): How chemical potential and their units are integrated in GMSO.
6. [GMSO_05_Forcefield_Schema.ipynb](./notebook/GMSO_05_Forcefield_Schema.ipynb): New Forcefield schema introduced by GMSO to promote more reproducible science.
7. [Example_Workflow.ipynb](./notebooks/Example_Workflow.ipynb): Demos a simulation workflow using features in gmso.
3. [GMSO_WIP_Features.ipynb](./notebooks/GMSO_WIP_Features.ipynb): Demos visualizing a gmso topology structure through plotly dash, this feature is a WIP in GMSO.
4. [pandas_convert.py](./notebooks/pandas_convert.py): Functions used in Plotly_Dash_Demo.ipynb tio convert the topology object to a pandas table.

## Usage
Clone this repository and create a new conda environment from the file [environment.yml](./environment.yml) and start jupyter.

```shell script
$ git clone https://github.com/mosdef-hub/gmso_showcase && cd gmso_showcase
$ conda env create --file environment.yml
$ jupyter notebook
```


Alternatively, you can directly launch this repository in [MyBinder](https://mybinder.org/v2/gh/umesh-timalsina/gmso_showcase/master).
