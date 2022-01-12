# Introdction

This code provides a Python implementation of Stein ICP presented in the paper:

"Stein ICP for Uncertainty Estimation in Point Cloud Matching", *RAL, 2021*.


# Installation

The code requires an NVidia GPU supported by PyTorch 1.6.0 or newer. A `requirements.txt` file is provided which contains the PIP installable requirements.

To facilitate the overall install a shell script `pip_install.sh` is provided.  

All required packages can be installed by executing the `pip_install.sh` script.


# Running

The code is provided in the form of a Jupyter notebook, as such running the code is achieved by starting the notebook via:

```
jupyter notebook
```

The code comes with two example point clouds which by default will be aligned using Stein ICP. To align different point clouds simply modify the source and target cloud paths.
