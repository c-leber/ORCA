# ORCA
Code in this branch is associated with **Chapter 4: *Moorena bouillonii* Chemogeography: Distributional Patterns of Compounds and Compound Families at Multiple Spatial Scales** from my dissertation.

*manuscript in prep*

ORCA stands for Objective Relational Comparative Analyses, as it was developed to study how different samples represented by multidimensional vectors (such as an MS1 peak table from LC-MS or LC-MS/MS chromatograms) are related to each other. The ORCA pipeline provides flexible MS1 feature detection and multivariate analyses, all in modular, interactive, and extendable format. Additional supporting documentation alongside the ORCA code base can be found in the "ORCA.ipynb" Jupyter Notebook file. The ORCA MS2 Auxiliary pipeline (tools for digging through mountains of MS2 data, and identifying patterns) and supporting documentation can be found in the "ORCA_MS2aux.ipynb" Jupyter Notebook file . The mzXML and mzML files analyzed in the above cited paper, as well as other associated files, can be found in the data directory.

![ORCA diagram](https://github.com/c-leber/ORCA/blob/master/ORCA_diagram.png)

Figure 1. from Leber CA et al (2020) **Applying a Chemogeographic Strategy for Natural Product Discovery from the Marine Cyanobacterium *Moorena bouillonii***. Mar Drugs 18:515. https://doi.org/10.3390/md18100515

Written in Python 3 (3.7.5)

Python Dependencies for ORCA and ORCA MS2 Auxilary (version used for development*):
- pandas (0.25.2)
- numpy (1.16.5)
- pyteomics (4.1.2)
- scipy (1.3.1)
- networkx (2.4)
- matplotlib (3.0.3) 
- sklearn (0.21.3)
- seaborn (0.9.0)

*ORCA will likely work fine with other versions of the above dependencies, but if you run into issue, try using the versions specified above.


Other useful tools to check out:
- Jupyter Notebook (https://jupyter.org/)
- MSconvert, for converting proprietary mass spec files to open source formats (e.g. mzXML, mzML) (http://proteowizard.sourceforge.net/tools.shtml)
- GNPS, for performing molecular networking with MS2 data (https://gnps.ucsd.edu/ProteoSAFe/static/gnps-splash.jsp)

***Please report issues if you run into any trouble! -Chris***
