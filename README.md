# python-for-applied-computing
Mini jupyter-based "textbook" for learning python for data and scientific computing

## What is this?

This is a mini "textbook" derived from the course notes for
CIS 161:  Computational Science at Grand Valley State University.
It is primarily designed to teach Python (specifically Python 3.x)
in the context of using Python to solve problems in data, science,
and mathematics.


## How to use it?

Rather than a traditional textbook, it is meant to be interactive.
To allow this, each "chapter" is a jupyter notebook.  There
are a few different ways you can use this "book".

### Static View Online
All of the notebooks are viewable directly online
in static form (cannot run and cannot modify).  Note,
this probably isn't as helpful as running interactively for learning
python, but can be helpful if you just need to consult something quick.

### Run Online with Google Colab (or myBinder)
This will open up the notebook on Google's Colab.  Google Colab is
a free service that allows you to run jupyter notebooks online.
* There is no need to install anything
* You can run cells, modify code, and add new cells
* To save your changes you have 2 options:
    * save a copy to your Google Drive "File" -> "Save a copy in drive"
    * save a copy to your Github "File" -> "Save a copy in github"
* Notes:
    * Colab uses a modified version of jupyter notebooks.
      All of the necessary functionality is there, but some
      of the options occur in slightly different locations.
    * Because this only copies the notebook (not related data files)
      you may see minor changes in the code (namely the use of `!wget url`
      to grab the datasets as well).

### Download Notebooks and Work Offline
To download all of the notebooks, click the green "Code" button and either
clone it (if you are familiar with git) or click the "Download zip" option
to get a zip file of everything.

To download an individual notebook, right click the links the links in the "Download Version"
column and select "save link as" (or the equivalent in your browser). 
To run the notebooks on your local machine, you will need to install
python3 and jupyter.  There are many ways to install python, but
[Anaconda Python](https://www.anaconda.com/products/individual)
is often one of the easiest prepackaged python distributions to
install that works on Windows, Mac, and Linux.


## Order
This "textbook" is meant to be worked with in the order listed below,
but you should feel free to jump around or skip sections based on
your previous experience with Python.

If you have no previous experience with Python, it is recommended
that you work up through section 10 in order.  After that, chapters
11 through 15 can be rearranged (with the exception that chapter 13 depends
on chapter 12).

## Chapters

| \#  | Topic | Static View | Run Online | Download Version |
| --- | ----- | ----------- | ---------- | ------------ |
| 01  | Intro - coming soon | | | |
| 02  | Basic Python - Variables & Operators | [View Online](notebooks/with-output/basic-python-variables-and-operators.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eecarrier/python-for-applied-computing/blob/main/notebooks/basic-python-variables-and-operators.ipynb) <br> [![Launch in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/eecarrier/python-for-applied-computing/HEAD?labpath=notebooks%2Fbasic-python-variables-and-operators.ipynb)) | [Work Offline](https://raw.githubusercontent.com/eecarrier/python-for-applied-computing/main/notebooks/basic-python-variables-and-operators.ipynb) |
| 03  | Using Jupyter Notebooks | [View Online](notebooks/with-output/notebooks-and-comments.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eecarrier/python-for-applied-computing/blob/main/notebooks/notebooks-and-comments.ipynb) <br> [![Launch in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/eecarrier/python-for-applied-computing/HEAD?labpath=notebooks%2Fnotebooks-and-comments.ipynb) | [Work Offline](https://raw.githubusercontent.com/eecarrier/python-for-applied-computing/main/notebooks/notebooks-and-comments.ipynb) |
| 04  | Functions | [View Online](notebooks/with-output/functions.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eecarrier/python-for-applied-computing/blob/main/notebooks/functions.ipynb) <br> [![Launch in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/eecarrier/python-for-applied-computing/HEAD?labpath=notebooks%2Ffunctions.ipynb) | [Work Offline](https://raw.githubusercontent.com/eecarrier/python-for-applied-computing/main/notebooks/functions.ipynb) |
| 05  | Math Module | [View Online](notebooks/with-output/math-module.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eecarrier/python-for-applied-computing/blob/main/notebooks/math-module.ipynb) <br> [![Launch in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/eecarrier/python-for-applied-computing/HEAD?labpath=notebooks%2Fmath-module.ipynb) | [Work Offline](https://raw.githubusercontent.com/eecarrier/python-for-applied-computing/main/notebooks/math-module.ipynb) |
| 06  | Conditionals | [View Online](notebooks/with-output/conditionals.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eecarrier/python-for-applied-computing/blob/main/notebooks/conditionals.ipynb) <br> [![Launch in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/eecarrier/python-for-applied-computing/HEAD?labpath=notebooks%2Fconditionals.ipynb) | [Work Offline](https://raw.githubusercontent.com/eecarrier/python-for-applied-computing/main/notebooks/conditionals.ipynb) |
| 07  | Loops | [View Online](notebooks/with-output/loops.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eecarrier/python-for-applied-computing/blob/main/notebooks/loops.ipynb) <br> [![Launch in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/eecarrier/python-for-applied-computing/HEAD?labpath=notebooks%2Floops.ipynb) | [Work Offline](https://raw.githubusercontent.com/eecarrier/python-for-applied-computing/main/notebooks/loops.ipynb) |
| 08  | Random Module | [View Online](notebooks/with-output/random-module.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eecarrier/python-for-applied-computing/blob/main/notebooks/random-module.ipynb) <br> [![Launch in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/eecarrier/python-for-applied-computing/HEAD?labpath=notebooks%2Frandom-module.ipynb) | [Work Offline](https://raw.githubusercontent.com/eecarrier/python-for-applied-computing/main/notebooks/random-module.ipynb) |
| 09  | Lists | [View Online](notebooks/with-output/lists.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eecarrier/python-for-applied-computing/blob/main/notebooks/lists.ipynb) <br> [![Launch in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/eecarrier/python-for-applied-computing/HEAD?labpath=notebooks%2Flists.ipynb) | [Work Offline](https://raw.githubusercontent.com/eecarrier/python-for-applied-computing/main/notebooks/lists.ipynb) |
| 10  | Strings| [View Online](notebooks/with-output/strings.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eecarrier/python-for-applied-computing/blob/main/notebooks/strings.ipynb) <br> [![Launch in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/eecarrier/python-for-applied-computing/HEAD?labpath=notebooks%2Fstrings.ipynb) | [Work Offline](https://raw.githubusercontent.com/eecarrier/python-for-applied-computing/main/notebooks/strings.ipynb) |
| 11  | Files | [View Online](notebooks/with-output/files.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eecarrier/python-for-applied-computing/blob/main/notebooks/colab-specific/files.ipynb) <br> [![Launch in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/eecarrier/python-for-applied-computing/HEAD?labpath=notebooks%2Ffiles.ipynb) | [Work Offline](https://raw.githubusercontent.com/eecarrier/python-for-applied-computing/main/notebooks/files.ipynb) |
| 12  | Tuples | [View Online](notebooks/with-output/tuples.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eecarrier/python-for-applied-computing/blob/main/notebooks/tuples.ipynb) <br> [![Launch in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/eecarrier/python-for-applied-computing/HEAD?labpath=notebooks%2Ftuples.ipynb) | [Work Offline](https://raw.githubusercontent.com/eecarrier/python-for-applied-computing/main/notebooks/tuples.ipynb) |
| 13  | Dictionaries | [View Online](notebooks/with-output/dictionaries.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eecarrier/python-for-applied-computing/blob/main/notebooks/dictionaries.ipynb) <br> [![Launch in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/eecarrier/python-for-applied-computing/HEAD?labpath=notebooks%2Fdictionaries.ipynb) | [Work Offline](https://raw.githubusercontent.com/eecarrier/python-for-applied-computing/main/notebooks/dictionaries.ipynb) |
| 14  | Plotting with Matplotlib | [View Online](notebooks/with-output/matplotlib.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eecarrier/python-for-applied-computing/blob/main/notebooks/matplotlib.ipynb) <br> [![Launch in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/eecarrier/python-for-applied-computing/HEAD?labpath=notebooks%2Fmatplotlib.ipynb) | [Work Offline](https://raw.githubusercontent.com/eecarrier/python-for-applied-computing/main/notebooks/matplotlib.ipynb) |
| 15  | Numpy | [View Online](notebooks/with-output/numpy-intro.ipynb) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eecarrier/python-for-applied-computing/blob/main/notebooks/colab-specific/numpy-intro.ipynb) <br> [![Launch in Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/eecarrier/python-for-applied-computing/HEAD?labpath=notebooks%2Fnumpy-intro.ipynb) | [Work Offline](https://raw.githubusercontent.com/eecarrier/python-for-applied-computing/main/notebooks/numpy-intro.ipynb) |



## License Info
Dataset licensing:
* `groundhog.csv` is CCO per the [Kaggle page it was obtained from](https://www.kaggle.com/groundhogclub/groundhog-day)
* `robert-frost.csv` is the full text of "Stopping by Woods on a Snowy Evening" by Robert Frost.
  As of Jan. 1, 2019 it is out of copyright and in the public domain
* `diabetes.csv` is CC0 per the [Kaggle page it was obtained from](https://www.kaggle.com/uciml/pima-indians-diabetes-database)

The remainder of the work is licensed under CC-BY-NC-SA.  See [full license text](license.md).
