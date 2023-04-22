# CS182-Proj-GNNs

## Dataset:
The dataset is the hiv.csv in the root directory. It contains molecule
represented in SMILES strings (which we convert to graph in the code),
and binary labels, with 1 meaning it is active against HIV and 0
otherwise. The data is part of MoleculeNet, and the version of the 
datset we used is taken from the repo
`https://github.com/chemprop/chemprop/blob/master/chemprop/features/featurization.py`

from the Barzilay group, which is a cleaned-up version of the original
MoleculeNet dataset.


(Unfinished) CoLab Link (view with .berkeley.edu account):

`https://colab.research.google.com/drive/1cg9HGtgGpWTLy2KYOSJ6H0DLvKFzMMGD?usp=sharingi`
Upload the hiv.csv dataset if it says it is not on CoLab.

Note that in CoLab, changes were made such that we are only training on atom features and
are ignoring bond features for simplicity.


