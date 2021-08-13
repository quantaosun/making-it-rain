# Making-it-rain
 Cloud-based molecular simulations for everyone

![alt text](https://github.com/pablo-arantes/Making-it-rain/blob/main/GraphAbs.png)

## Hello there!

This is a repository where you can find a Jupyter notebook scripts for running Molecular Dynamics (MD) simulations using OpenMM engine and AMBER and CHARMM force fields files on Google Colab. This repository is a supplementary material of the paper "***Making it rain: Cloud-based molecular simulations for everyone***" and we encourage you to read it before using this pipeline.

The main goal of this work is to demonstrate how to harness the power of cloud-computing to run microsecond-long MD simulations in a cheap and yet feasible fashion.

- **AMBER** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Making-it-rain/blob/main/Amber.ipynb)  - `Using AMBER to generate topology and to build the simulation box`
- **CHARMM** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Making-it-rain/blob/main/CHARMM_GUI.ipynb) - `Using inputs from CHARMM-GUI solution builder`
- **AlphaFold2+MD** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Making-it-rain/blob/main/AlphaFold2%2BMD.ipynb) - `Using AlphaFold2_mmseqs2 to generate protein model + MD simulation using AMBER to generate topology and to build simulation box`

![alt text](https://github.com/pablo-arantes/Making-it-rain/blob/main/fluxogram_gh.png)


## Bugs
- If you encounter any bugs, please report the issue to https://github.com/pablo-arantes/Making-it-rain/issues

## Acknowledgments

- We would like to thank the OpenMM team for developing an excellent and open source engine. 
- We would like to thank the AlphaFold team for developing an excellent model and open sourcing the software. 
- Credit to Sergey Ovchinnikov ([@sokrypton](https://twitter.com/sokrypton)), Milot Mirdita ([@milot_mirdita](https://twitter.com/milot_mirdita)) and Martin Steinegger ([@thesteinegger](https://twitter.com/thesteinegger)) for their fantastic [ColabFold](https://github.com/sokrypton/ColabFold)
- A RAIN by **Pablo R. Arantes** ([@pablitoarantes](https://twitter.com/pablitoarantes)), **Marcelo D. Polêto** ([@mdpoleto](https://twitter.com/mdpoleto)), **Conrado Pedebos** ([@ConradoPedebos](https://twitter.com/ConradoPedebos)) and **Rodrigo Ligabue-Braun** ([@ligabue_braun](https://twitter.com/ligabue_braun)).
- Also, credit to [David Koes](https://github.com/dkoes) for his awesome [py3Dmol](https://3dmol.csb.pitt.edu/) plugin.

## Do you want to cite this work?

[![DOI](https://zenodo.org/badge/393463171.svg)](https://zenodo.org/badge/latestdoi/393463171)
