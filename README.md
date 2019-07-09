# clapy - Analyse continuous labelling assays


`clapy` is a python3 module that allows to analyse continuous labelling assays.


### Requirements

You will need  `matplotlib`, `numpy`, `iminuit` and `scipy`. For the basic fitting.
To recreate our plots you will also need `pandas`, `seaborn`. 
To have nice plots you need also a working latex render backend for matplotlib.
If not do not run cell 3 of paper_plots.ipynb.


### Recreate the Plot from our Paper
Please decompress the data file 'paper_data.pandas.gz' for the plots first! 
'gzip -d paper_data.pandas.gz'
The data file can be created with paper_simulations.ipynb, which need our cla simulator:
https://github.com/fabianrost84/clasim

To have nice plots you need also a working latex render backend for matplotlib.
If not do not run cell 3 of paper_plots.ipynb.


## How to cite `clapy`

We will soon publish a preprint about the underlying model. Please cite this
preprint if you find cla usefull for your research.
