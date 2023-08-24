# Awesome DMFT solvers [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of resources for Dynamical Mean-Field Theory (DMFT). This includes: softwares, references, databases, youtube talks.

This list might be imcomplete, so that contributions are very welcome and encouraged. If you want to contribute, please follow the [guidelines](CONTRIBUTING.md) and the [Code of Conduct](code_of_conduct.md). 

## Software

- [TRIQS](https://triqs.github.io/triqs/latest/): A set of C++ and Python libraries used to develop new tools for studying interacting quantum systems.

    - [solid_dmft](https://github.com/TRIQS/solid_dmft): A versatile python wrapper to perform DFT+DMFT calculations utilizing the TRIQS software library.

    - [DFTtools](https://github.com/TRIQS/dft_tools): A TRIQS-based toolbox for ab-initio DFT calculations and useful to interface with DMFT calculations.

- [w2dynamics](https://github.com/w2dynamics/w2dynamics): A CT-HYB package for calculating n-particle Green's functions of the AIM developed in Wien/Würzburg. 

- [embeddedDMFT / eDMFT](http://hauleweb.rutgers.edu/tutorials/): A package implementing DFT+DMFT derived from the stationary Luttinger-Ward functional.

- [DMFTwDFT](https://github.com/DMFTwDFT-project/DMFTwDFT): A framework combining DMFT with various DFT packages.

- [DCore](https://github.com/issp-center-dev/DCore): A package combining lattice models and ab-initio DFT calculations with DMFT calculations.

- [pomerol](https://github.com/pomerol-ed/pomerol): An ED solver package written in C++ aimed at solving models of interacting fermions and bosons on finite size lattices at finite temperatures.

- [iQIST](https://github.com/huangli712/iQIST): A package containing several CT-HYB solvers and auxiliary scripts. 

## References

### Must-read

- A. Georges et al., _Dynamical mean-field theory of strongly correlated fermion systems and the limit of infinite dimensions_, [Rev. Mod. Phys. **68**, 13 (1996)](https://journals.aps.org/rmp/abstract/10.1103/RevModPhys.68.13): A review introducing DMFT, providing the theoretical framework and explaining the physical ideas derived from mapping lattice models onto single-impurity models.

- W. Metzner and D. Vollhardt, _Correlated Lattice Fermions in d=∞ Dimensions_, [Phys. Rev. Lett. **62**, 324 (1989)](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.62.324): A paper presenting the concept of mapping a lattice model onto an auxiliary impurity model in infinite dimensions.

- A. Georges and G. Kotliar, _Hubbard model in infinite dimensions_, [Phys. Rev. B **45**, 6479 (1992)](https://journals.aps.org/prb/abstract/10.1103/PhysRevB.45.6479): A paper providing a detailed application of DMFT to the Hubbard model by exploring the phase diagram and spectral properties.

- G. Kotliar et al., _Electronic structure calculations with dynamical mean-field theory_, [Rev. Mod. Phys. **78**, 865 (2006)](https://journals.aps.org/rmp/abstract/10.1103/RevModPhys.78.865): A review of the basic ideas and techniques used in electronic structure calculations with DMFT.

- M. Caffarel and W. Krauth, _Exact diagonalization approach to correlated fermions in infinite dimensions: Mott transition and superconductivity_, [Phys. Rev. Lett. **72**, 1545 (1994)](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.72.1545): A paper introducing the ED method for calculating properties of the infinite dimension Hubbard model.

- P. Werner et al., _Continuous-Time Solver for Quantum Impurity Models_, [Phys. Rev. Lett. **97**, 076405 (2006)](https://journals.aps.org/prl/abstract/10.1103/PhysRevLett.97.076405): A paper introducing the CT-QMC method for solving impurity problems within DMFT.

## Databases

- [NOMAD](https://nomad-lab.eu/nomad-lab/): A materials science database which can parse DMFT codes and have DMFT and Green's functions metadata schemas.

## Youtube Talks

- [Dynamical Mean-Field Theory at CECAM-MARVEL](https://www.youtube.com/watch?v=mfiXx0dS-QQ): A lecture given by Antoine Georges and Gabriel Kotliar on DMFT. December 8, 2022.

- [Dynamical Mean Field Theory](https://www.youtube.com/watch?v=MvElAkE5tz4): An introductory course lecture given by Maurits Haverkort. July 8, 2021.

## Abbreviations

- **DMFT**: Dynamical Mean-Field Theory
- **DFT**: Density Functional Theory
- **AIM**: Anderson Impurity Model
- **CT-HYB**: Continous-Time Hybridization-expansion Monte Carlo
- **ED**: Exact Diagonalization
- **CT-QMC**: Continous-Time Quantum Monte Carlo
