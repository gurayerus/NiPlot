# [NiPlot] Neuro-imaging data plotting


**[NiPlot]** is a toolbox for plotting imaging and non-imaging data.

## Setup for development
Install Python version 3.8.8 or newer.
The exact procedure depends on the operating system and configuration.
Verify the version with

```shell
python --version # should be 3.8.8 or newer
```

### Prepare conda environment
Assuming current working directory is `NiPlot` and containing the source code
cloned from https://github.com/CBICA/NiPlot.git.

Ensure Anaconda is installed. Follow instructions for user's operating system [here](https://docs.anaconda.com/anaconda/install/index.html). After Anaconda has been installed, be sure to exit and reopen any 
command line windows to use `conda` command

```shell
conda create -n NiPlot python=3.8.8  
conda activate NiPlot
python -m pip install --upgrade pip
```

### Prepare environment in Linux (CUBIC)
Assuming current working directory is `NiPlot` and containing the source code
cloned from https://github.com/gurayerus/NiPlot.git.

```shell
python -m venv .env
.env/bin/activate
python -m pip install --upgrade pip
```

### Prepare environment for PowerShell (Windows 10 or 11)
Assuming current working directory is `NiChart` and containing the source code
cloned from https://github.com/gurayerus/NiChart.git.

```shell
python -m venv .env
& .env/Scripts/Activate.ps1
python -m pip install --upgrade pip
```

### Install the [NiPlot] software
To install the [NiPlot], install it in a virtual or conda environment.
Depending on the desired version, use one of the following
commands to install it.

```shell
# Editable version for development after cloning https://github.com/gurayerus/NiPlot.git 
python -m pip install -U -e .

# Main version of toolbox
python -m pip install -U git+https://github.com/gurayerus/NiPlot.git
```

## Usage
After proper installation, the standalone graphical user interface can be launched
in the terminal with:

```shell
NiPlot
```

The data file can be passed as command line argument `--data_file` as shown below.

```shell
NiPlot --data_file data.csv
```

## Disclaimer
- The software has been designed for research purposes only and has neither been reviewed nor approved for clinical use by the Food and Drug Administration (FDA) or by any other federal/state agency.

## Contact
For more information and support, please post on the [Discussions](https://github.com/gurayerus/NiPlot/discussions) section
