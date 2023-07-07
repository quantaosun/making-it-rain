# Making-it-rain
 Cloud-based molecular simulations for everyone

```diff
+ 28Apr2023: We have updated all the notebooks to Python 3.10, everything is working fine
+ 01May2023: We have fixed the Amber, AlphaFol2+MD and Protei-Ligand notebooks. 
```

![alt text](https://github.com/pablo-arantes/Making-it-rain/blob/main/GraphAbs.png)


## Hello there!

This is a repository where you can find a Jupyter notebook scripts for running Molecular Dynamics (MD) simulations using OpenMM engine and AMBER and CHARMM force fields files on Google Colab. This repository is a supplementary material of the paper "***Making it rain: Cloud-based molecular simulations for everyone***" and we encourage you to read it before using this pipeline.

The main goal of this work is to demonstrate how to harness the power of cloud-computing to run microsecond-long MD simulations in a cheap and yet feasible fashion.

**Important**: We've updated the notebooks to [CondaColab](https://github.com/conda-incubator/condacolab). Now, all the dependencies will be installed faster than before (less than half of the previous time). You will see a CondaColab cell, just run and wait a few seconds, the session will restart and this is **normal and expected**. After that, you can continue running the cells like normal. Do not use the `Run all` option. Run the `condacolab` cell _individually_ and wait for the kernel to restart. **Only then**, you can run all cells if you want. Thank you for your support.

1. **AMBER** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Making-it-rain/blob/main/Amber.ipynb)  - `Using AMBER to generate topology and to build the simulation box`
2. **CHARMM** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Making-it-rain/blob/main/CHARMM_GUI.ipynb) - `Using inputs from CHARMM-GUI solution builder`
3. **AlphaFold2+MD** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/Making-it-rain/blob/main/AlphaFold2%2BMD.ipynb) - `Using AlphaFold2_mmseqs2 to generate protein model + MD simulation using AMBER to generate topology and to build simulation box`


**UPDATE (October 2021)**

4. **Protein-Ligand simulations** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/making-it-rain/blob/main/Protein_ligand.ipynb)  - `Using AMBER to generate topology and to build the simulation box and for the ligand using GAFF2 force field`
5. **Using AMBER Inputs** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/making-it-rain/blob/main/Amber_inputs.ipynb)  - `Using inputs from AMBER suite of biomolecular simulation program`
6. **Using GROMACS Inputs** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/making-it-rain/blob/main/Gromacs_inputs.ipynb)  - `Using inputs from GROMACS biomolecular simulation package (AMBER, CHARMM and OPLS force fields are compatible)`

**UPDATE (March 2022)**

7. **RESP Partial Charges** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/making-it-rain/blob/main/Partial_Charges.ipynb)  - `Using a SMILES as input and outputs a mol2 file with RESP derived partial charges. Options for setting method (HF, B3LYP, ...), basis set (3-21G, 6-31G*) and singlepoint or geometry optimization are available`
8. **Small Molecules MD** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/making-it-rain/blob/main/MD_Small_Molecules.ipynb)  - `Using a SMILES as a input, geometry optimization with TorchANI and topology with AMBER (GAFF2 force field)`
9. **GLYCAM** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/making-it-rain/blob/main/Glycam.ipynb)  - `Using inputs from GLYCAM server`

**UPDATE (August 2022)**

10. **DRUDE** [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/pablo-arantes/making-it-rain/blob/main/Drude.ipynb)  - `Using inputs from CHARMM-GUI Drude Prepper`

![alt text](https://github.com/pablo-arantes/Making-it-rain/blob/main/fluxogram_gh.png)


## Bugs
- If you encounter any bugs, please report the issue to https://github.com/pablo-arantes/Making-it-rain/issues

## Acknowledgments

- We would like to thank the [Psi4](https://psicode.org/) team for developing an excellent and open source suite of ab initio quantum chemistry.
- We would like to thank the [Roitberg](https://roitberg.chem.ufl.edu/) team for developing the fantastic [TorchANI](https://github.com/aiqm/torchani).
- We would like to thank the OpenMM team for developing an excellent and open source engine. 
- We would like to thank the AlphaFold team for developing an excellent model and open sourcing the software. 
- We would like to thank the ChemosimLab ([@ChemosimLab](https://twitter.com/ChemosimLab)) team for their incredible [ProLIF](https://prolif.readthedocs.io/en/latest/index.html#) (Protein-Ligand Interaction Fingerprints) tool.
- Credits to Sergey Ovchinnikov ([@sokrypton](https://twitter.com/sokrypton)), Milot Mirdita ([@milot_mirdita](https://twitter.com/milot_mirdita)) and Martin Steinegger ([@thesteinegger](https://twitter.com/thesteinegger)) for their fantastic [ColabFold](https://github.com/sokrypton/ColabFold)
- Making it rain by **Pablo R. Arantes** ([@pablitoarantes](https://twitter.com/pablitoarantes)), **Marcelo D. Polêto** ([@mdpoleto](https://twitter.com/mdpoleto)), **Conrado Pedebos** ([@ConradoPedebos](https://twitter.com/ConradoPedebos)) and **Rodrigo Ligabue-Braun** ([@ligabue_braun](https://twitter.com/ligabue_braun)).
- Also, credit to [David Koes](https://github.com/dkoes) for his awesome [py3Dmol](https://3dmol.csb.pitt.edu/) plugin.
- Finally, we would like to thank Professor [Giulia Palermo](https://palermolab.com/) for her support and thoughtful comments in the development of the present work.

## Do you want to cite this work?


Arantes P.R., Depólo Polêto M., Pedebos C., Ligabue-Braun R. Making it rain: cloud-based molecular simulations for everyone. 
Journal of Chemical Information and Modeling 2021. DOI: [10.1021/acs.jcim.1c00998](https://doi.org/10.1021/acs.jcim.1c00998).

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5196783.svg)](https://doi.org/10.5281/zenodo.5196783)
##
<a href="https://trackgit.com">
<img src="https://us-central1-trackgit-analytics.cloudfunctions.net/token/ping/ksghbo50inl9a2at7yks" alt="trackgit-views" />
</a>
