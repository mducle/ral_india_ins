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

---

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons Licence" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/80x15.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Excitations Data Analysis Training Course Materials</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/pace-neutrons/edatc" property="cc:attributionName" rel="cc:attributionURL">M. D. Le and others</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/pace-neutrons/edatc" rel="dct:source">https://github.com/pace-neutrons/edatc</a>.
