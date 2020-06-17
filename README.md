# ATM Notebooks
Jupyter Notebooks for Asteroid Thermal Modeling in Python  
[![Docker Pulls](https://img.shields.io/docker/pulls/moeyensj/atm_notebooks)](https://hub.docker.com/r/moeyensj/atm_notebooks)
[![License](https://img.shields.io/badge/License-BSD%203--Clause-blue.svg)](https://opensource.org/licenses/BSD-3-Clause)

## Installation

For more details on the package see: https://github.com/moeyensj/atm.

First, complete the installation directions for the ATM package, then clone this repository using either `ssh` or `https` into the same directory level as the ATM code. For example:

```
ls projects/atm/
    atm
    atm_notebooks
```

Activate the conda enviroment in which ATM dependencies were installed, then install additional dependencies:  
```conda install -c defaults -c conda-forge --file additional_requirements.txt```

To install pre-requisite software using pip:  
```pip install -r additional_requirements.txt```

### Docker

A Docker container with the latest version of the ATM notebooks and code can be pulled using:  
```docker pull moeyensj/atm_notebooks:latest```

To run the container (feel free to map the ports differently):  
```docker run -it --rm -p 1719:1719 moeyensj/atm_notebooks:latest```
