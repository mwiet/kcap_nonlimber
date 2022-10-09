# kcap_nonlimber

The repository is an expansion of the KCAP module which can be found [here](https://github.com/KiDS-WL/kcap). To use the code in this repository, simply copy the files in the utils folder into the kcap/utils folder.

KCAP-nonLimber implements a new methodology to project 3D power spectra to 2D angular power spectra within the nonLimber module (Reischke et al. in prep.). This is achieved using the Levin method [Levin 1994](https://www.sciencedirect.com/science/article/pii/0377042794001189) and the code is available [here](https://github.com/rreischke/nonLimber_matter_shells).

## Installation

Firstly, we have to install the nonLimber, a.k.a. levinpower, module:

```
git clone https://github.com/rreischke/nonLimber_matter_shells.git
cd nonLimber_matter_shells
pip install .
```

Then, we clone the KCAP repository:
```
git clone https://github.com/KiDS-WL/kcap.git
cd kcap/utils
```

Next, we copy all the files in the utils folder of this respository into the kcap/utils folder.

Then, we proceed with the installation of the KCAP module as outlined [here](https://github.com/KiDS-WL/kcap). Note that the modules can also be copied into kcap after installation.
