# ORCA
Code associated with ORCA manuscript: XX

Dependencies for ORCA:
- XX
- XX
- XX
import pandas as pd
import numpy as np
from pyteomics import mzxml, auxiliary
import glob
from scipy.spatial.distance import pdist, squareform
import itertools
import networkx as nx
from statistics import mean
import matplotlib 
from matplotlib import pyplot as plt
from scipy.cluster.hierarchy import dendrogram, linkage, cophenet
from collections import Counter
import sklearn.feature_selection
import seaborn as sns; sns.set()

Dependencies for ORCA MS2 Auxilary:

pandas as pd
import numpy as np
from pyteomics import mzml, auxiliary
import glob
import matplotlib 
from matplotlib import pyplot as plt
from scipy.cluster.hierarchy import dendrogram, linkage, cophenet, set_link_color_palette, fcluster
from collections import Counter

%matplotlib inline



Other useful tools to check out:
- MSconvert
- GNPS
