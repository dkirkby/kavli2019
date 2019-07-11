# Kavli Summer Program in Astrophysics Lectures

Lectures on machine learning for the [Kavli Summer Program in Astrophysics](https://kspa.soe.ucsc.edu/) hosted by UC Santa Cruz in July 2019:
 - [Practical Bayesian Inference](https://nbviewer.jupyter.org/format/slides/github/dkirkby/kavli2019/blob/master/Lecture1.ipynb#/) [[notebook](https://nbviewer.jupyter.org/github/dkirkby/kavli2019/blob/master/Lecture1.ipynb)]
 - [Unsupervised Deep Learning](https://nbviewer.jupyter.org/format/slides/github/dkirkby/kavli2019/blob/master/Lecture2.ipynb#/) [[notebook](https://nbviewer.jupyter.org/github/dkirkby/kavli2019/blob/master/Lecture2.ipynb)]

The slides are based on jupyter notebooks that contain all of the code used for the examples and plots (usually in cells that the slideshow skips).  Use the *[notebook]* links above to view these notebooks. To run the notebooks yourself, you can download them and create a conda environment with the necessary packages:
```
git clone https://github.com/dkirkby/kavli2019
cd kavli2019
conda env create -f environment.yml
conda activate K19
jupyter notebook
```

If you are interested in presenting your own notebooks as a slideshow, see [here](https://medium.com/@mjspeck/presenting-code-using-jupyter-notebook-slides-a8a3c3b59d67) for an overview.  There are two important caveats (as of July 2019):
 - The slideshow feature currently only works with the older `jupyter notebook` front end, not the new `jupyter lab`.
 - You cannot reliably edit or run cells from within the slideshow (the [RISE package](https://github.com/damianavila/RISE) is designed for this, but was not reliable for me).

If find errors or have suggestions for improvement, please [create an issue](https://github.com/dkirkby/kavli2019/issues/new).

 All material is (c) 2019 David Kirkby <dkirkby@uci.edu> and released under an MIT License.