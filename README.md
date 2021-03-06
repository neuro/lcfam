# lcfam
Generate lightness corrected color-coded fractional anisotropy maps (LCFAMs).

<img src="https://s3.eu-central-1.amazonaws.com/jan-gerd-tenberge-research/lcfam/demo.png">

## Requirements
For the command line utility you will need Python 2.7 and scikit-image, which can be installed with

    pip install scikit-image

the IPython notebook has additional requirements for the visualisation of the results. These can be installed with

    pip install ipython[all]
    pip install scikit-image
    pip install seaborn

## Jupyter Notebook
Run the Jupyter notebook on your local computer or see it online at http://nbviewer.ipython.org/github/janten/lcfam/tree/master/lcfam.ipynb.

## Command Line Utility
To create an LCFAM from the comman line, use `lcfam.py`:

    $ python lcfam.py <cfam.png> <fam.png> <outfile.png>
