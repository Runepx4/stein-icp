# Introdction

This code provides a Python implementation of Stein ICP presented in the paper:

"Stein ICP for Uncertainty Estimation in Point Cloud Matching" submitted for review to *RAL, 2021*.


# Installation

The code requires an NVidia GPU supported by PyTorch 1.6.0 or newer. A `requirements.txt` file is provided which contains the PIP installable requirements.

To facilitate the overall install a shell script `pip_install.sh` is provided. Adjusting the variables at the top of the file for the system's PyTorch and CUDA version allow for an easy installation of all required packages. 

Once the `pip_install.sh` file is adjusted all required packages can be installed by executing the script.


# Running

The code is provided in the form of a Jupyter notebook, as such running the code is achieved by starting the notebook via:

```
jupyter notebook
```

The code comes with two example point clouds which by default will be aligned using Stein ICP. To align different point clouds simply modify the source and target cloud paths.
