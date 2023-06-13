# INS Course Materials

This page contains course materials for the inelastic neutron scattering (INS) data analysis course in the [Workshop on Data Analysis of Neutron Scattering](https://www.jncasr.ac.in/facilities/neutron-muon/workshop), as part of the RAL-India Neutron and Muon Science Meeting, June 12-16, 2023 at JNCASR, Bangalore.

## Program Installation

The examples all need Python in a Conda environment to run.
If you don't have Conda/Anaconda installed, we recommend to use [micromamba](https://github.com/conda-forge/miniforge#mambaforge) - please install the `mambaforge` installer for your OS and start it.

In the conda command prompt, please then run:

```bash
mamba create -n ralindia -c conda-forge python=3.8
mamba activate ralindia
mamba install -c mantid mantidworkbench
pip install jupyter spinw
```

Note that if you have Anaconda/miniconda installed please replace `mamba` with `conda`.
You must use Python 3.8 (unfortunately Mantid currently only supports Python 3.8).
You can use another environment name than `ralindia` but please replace all instance of this name with what you choose.
The installation of `mantidworkbench` will take quite a long time (~15-30 min).
