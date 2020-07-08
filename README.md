# ORCA
Code associated with ORCA manuscript: XX

The ORCA pipeline (flexible MS1 feature detection and multivariate analyses) and supporting documentation can be found in the XX Jupyter Notebook file. The ORCA MS2 Auxiliary pipeline (tools for digging through mountains of MS2 data, and identifying patterns) and supporting documentation can be found in the XX Jupyter Notebook file . The mzXML and mzML files analyzed in the paper can be found in the data directory.

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
