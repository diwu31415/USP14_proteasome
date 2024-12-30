# Simulation of USP14 regulated substrate degradation in 26S proteasome

This repository contains the source codes and result data for the simulation of USP14 regulated substrate degradation in 26S proteasome.

## Requirements

The entire project is based on Python and Jupyter Notebook. To open and run the source code in notebook files, a Python (3.8.15) and a Jupyter Notebook installation is required. The following Python packages are also required:

* numpy (1.22.4)
* matplotlib (3.6.2)
* scipy (1.7.3)

We only tested the code under the versions of Python and packages mentioned above. Although it may still work under other versions, we recommend running the code with the same versions as our testing environment to ensure that all results can be reproduced correctly. 

If other versions of Python and packages are already installed, please use virtualenv or conda to create a virtual environment for this project.

## Files

* `model.ipynb`: Simulating the dynamic of substrate degradation in 26S proteasome.
* `sensitivity_analysis.ipynb`: Generate the sensitivity analysis result as shown in Supplementary.

## How to use

The code can be obtained by running:

```bash
$ git clone https://github.com/diwu31415/USP14_proteasome
```

or simply click "Code -> Download Zip" on this page.

After cloning or downloading and unpacking is complete, open the notebook files with your favorite Jupyter-supported editor (e.g. VScode with Jupyter plugin).

Afterward, you can browse and execute the code in the notebook files in the same way as you operate other notebook files.