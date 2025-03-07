# indoor_environment_PyCHAM_setup
setup the necessary files for simulating indoor environments using PyCHAM

This computer algorithm creates the input files required for the CHemistry with Aerosol Microphysics in Python (PyCHAM) computer box model to simulate indoor environments, such as households. To do this, the algorithm draws on gas-phase and particle-phase observations of outdoor chemical species, along with reported gas-phase and particle-phase emission rates of chemical species from indoor activities (e.g. personal care products). The user defines other variables, such as: the volume of indoor environment being simulated, the air change rate, the frequency and timing of indoor activities. On completion of the algorithm, the user passes the generated model variables file to the PyCHAM model software (https://github.com/simonom/PyCHAM) for simulation.

The src/package layout is explained [here](https://www.pyopensci.org/python-package-guide/package-structure-code/python-package-structure.html)
