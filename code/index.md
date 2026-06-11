# Code

## Snapshot Retrieval Framework: **Brewster_V2**

<details>
<summary>GitHub</summary>

https://github.com/fwang23nh/brewster_v2

</details>

**Brewster_V2** is an upgraded version of the original Brewster framework (https://github.com/substellar/brewster), designed for atmospheric retrievals of exoplanets and brown dwarfs. The code combines radiative transfer calculations with statistical inference techniques to constrain atmospheric properties such as temperature structure, chemical abundances, cloud properties, and bulk properties.

It is optimized for interpreting observations from facilities including JWST, HST, and ground-based instruments, and supports flexible atmospheric parameterizations suitable for a wide range of substellar atmospheres.

**Features**

* Bayesian atmospheric retrieval using nested sampling / MCMC methods  
* Multi-instrument compatibility (JWST, HST, ground-based spectra)  
* Cloud, chemistry, and temperature parameterizations  
* High-performance likelihood evaluation and modular architecture  

**GitHub:**  
https://github.com/fwang23nh/brewster_v2

---

## Time-resolved Retrieval Framework: **Tempawral**

**Tempawral** is a time-resolved atmospheric retrieval framework developed to characterize rotational variability in brown dwarfs and directly imaged exoplanets. Instead of treating each spectrum independently, Tempawral models the temporal evolution of spectral variability using a data-driven eigen-spectra decomposition, enabling robust inference of the physical mechanisms driving atmospheric changes.

The framework is particularly suited for JWST time-series spectroscopy and can be used to investigate the roles of clouds, chemistry, temperature perturbations, and auroral processes in producing observed variability. It provides a generalizable approach for atmospheric characterization in the era of high-precision time-domain observations.

**Features**

* Time-resolved atmospheric retrievals  
* Eigen-spectra / data-driven variability decomposition  
* Joint inference across rotational phase-resolved spectra  
* Designed for JWST time-series spectroscopic datasets  
* Physical interpretation of variability: clouds, chemistry, temperature, aurorae  
* Modular framework for extension to new instruments and targets  

**GitHub:**  
https://github.com/fwang23nh/Tempawral