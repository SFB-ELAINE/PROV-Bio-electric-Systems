# PROV-Bio-electric-Systems

A collection of W3C PROVenance models for the numerical modelling and finite element simulation processes of bio-electric systems.
Details about these models can be found in

M. Schröder, H. Raben, F. Krüger, A. Ruscheinski, U. van Rienen, A. Uhrmacher, and S. Spors, “PROVenance Patterns in Numerical Modelling and Finite Element Simulation  Processes of Bio-electric Systems,” 41st Annual International Conference of the IEEE Engineering in Medicine and Biology Society (EMBC), Jul. 2019. To Appear.

## Usage

The folder `model-based` contains a set of provenance models that correspond to the process described in

U. van Rienen, U. Zimmermann, H. Raben, and P. W. Kämmerer, “Preliminary numerical study on electrical stimulation at alloplastic reconstruction plates of the mandible,” Scientific Computing in Electrical Engineering, Jan. 2018. [Online]. Available: http://dx.doi.org/10.1007/978-3-319-75538-0_1

Along with the model, we provide a set of pattern (`model-based/pattern`), that we identified during analysis.

In order to visualise the Turtle specification (`*.ttl` files) the Jupyter notebook `PROV-Model Visualisation.ipynb` was used.
To execute this notebook, make sure the `requirements.txt` are installed appropriately:

```
pip install -r requirements.txt
```

The software was tested using Jupyter v4.4.0 and Python v3.5.3.
Alternatively, launch this repository in mybinder.org:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/SFB-ELAINE/PROV-Bio-electric-Systems/master)

## License

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/88x31.png)](http://creativecommons.org/licenses/by/4.0/)

This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/), please attribute them as:

Max Schröder, Hendrikje Raben, Frank Krüger, Andreas Ruscheinski, Ursula van Rienen, Adelinde Uhrmacher, and Sascha Spors, “PROVenace Models for Bio-electric Systems,” https://github.com/SFB-ELAINE/PROV-Bio-electric-Systems
