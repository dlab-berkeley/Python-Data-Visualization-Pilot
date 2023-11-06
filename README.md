# D-Lab's Python Data Visualization Workshop

[![Datahub](https://img.shields.io/badge/launch-datahub-blue)](https://dlab.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FPython-Data-Visualization-Pilot&urlpath=lab%2Ftree%2FPython-Data-Visualization-Pilot%2F&branch=main)
[![Binder](http://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/dlab-berkeley/Python-Data-Visualization-Pilot/HEAD)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository contains the materials for D-Lab's Python Data Visualization workshop. We
recommend attending [Python Fundamentals](https://github.com/dlab-berkeley/python-fundamentals) prior to taking this workshop.

Check D-Lab's [Learning Pathways](https://dlab-berkeley.github.io/dlab-workshops/python_path.html) to figure out which of our workshops to take!


## Workshop Goals

In this workshop, we provide an introduction to data visualization with Python. First, we'll cover some basics of visualization theory. Then, we'll explore how to plot data in Python using the `matplotlib` and `seaborn` packages. We aim to cover the following types of plots:

* Histograms
* Bar plots
* Boxplots
* Scatter plots
* Line plots

## Learning Objectives

After this workshop, you will be able to:

- Understand the general principles and common pitfalls of data visualization.
- Gain familarity with key features of python plotting libraries, namely matplotlib and seaborn.
- Use seaborn to visualize plots.
- Apply codes to customize plots.

This workshop does not cover the following:

- Working with Pandas DataFrames. This is covered in [Python Data Wrangling](https://github.com/dlab-berkeley/Python-Data-Wrangling).
- Python basics. These are covered in [Python Fundamentals](https://github.com/dlab-berkeley/Python-Fundamentals).


## Installation Instructions

Anaconda is a useful package management software that allows you to run Python and Jupyter notebooks very easily. Installing Anaconda is the easiest way to make sure you have all the necessary software to run the materials for this workshop. Complete the following steps:

1. [Download and install Anaconda (Python 3.8 distribution)](https://www.anaconda.com/products/individual). Click "Download" and then click 64-bit "Graphical Installer" for your current operating system.

2. Download the [Python-Data-Visualization workshop materials](https://github.com/dlab-berkeley/Python-Data-Visualization):

* Click the green "Code" button in the top right of the repository information.
* Click "Download Zip".
* Extract this file to a folder on your computer where you can easily access it (we recommend Desktop).

3. Optional: if you're familiar with `git`, you can instead clone this repository by opening a terminal and entering `git clone git@github.com:dlab-berkeley/Python-Data-Visualization.git`.

## Run the code

Now that you have all the required software and materials, you need to run the code:

1. Open the Anaconda Navigator application. You should see the green snake logo appear on your screen. Note that this can take a few minutes to load up the first time. 

2. Click the "Launch" button under "Jupyter Notebooks" and navigate through your file system to the `Python-Data-Visualization` folder you downloaded above.

3. Open the `lessons` folder, and click `Python-Data-Visualization.ipynb` to begin.

4. Press Shift + Enter (or Ctrl + Enter) to run a cell.

5. By default, the necessary packages for this workshop should already be installed. You can install them within the Jupyter notebook by running the following line in its own cell:

> ```!pip install -r requirements.txt```

Note that all of the above steps can be run from the terminal, if you're familiar with how to interact with Anaconda in that fashion. However, using Anaconda Navigator is the easiest way to get started if this is your first time working with Anaconda.

## Is Python not working on your laptop? 

If you do not have Anaconda installed and the materials loaded on your workshop by the time it starts, we *strongly* recommend using the UC Berkeley Datahub to run the materials for these lessons. You can access the DataHub by clicking this button: 

[![Datahub](https://img.shields.io/badge/launch-datahub-blue)](https://dlab.datahub.berkeley.edu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fdlab-berkeley%2FPython-Data-Visualization&urlpath=tree%2FPython-Data-Visualization%2F&branch=main)

The DataHub downloads this repository, along with any necessary packages, and allows you to run the materials in a Jupyter notebook that is stored on UC Berkeley's servers. No installation is necessary from your end - you only need an internet browser and a CalNet ID to log in. By using the DataHub, you can save your work and come back to it at any time. When you want to return to your saved work, just go straight to [DataHub](https://dlab.datahub.berkeley.edu), sign in, and you click on the `Python-Data-Visualization` folder.

If you don't have a Berkeley CalNet ID, you can still run these lessons in the cloud, by clicking this button:

[![Binder](http://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/dlab-berkeley/Python-Data-Visualization/HEAD)

By using this button, however, you cannot save your work.

# Additional Resources

Check out the following resources to learn more about data visualization:

* [Matplotlib tutorials](https://matplotlib.org/stable/tutorials/index.html)

* [Seaborn tutorials](https://seaborn.pydata.org/tutorial.html)

* Go further with the [plotly](https://plotly.com/), [bokeh](http://docs.bokeh.org/en/latest/), and [dash](https://plotly.com/dash/) packages.

# About the UC Berkeley D-Lab

D-Lab works with Berkeley faculty, research staff, and students to advance data-intensive social science and humanities research. Our goal at D-Lab is to provide practical training, staff support, resources, and space to enable you to use R for your own research applications. Our services cater to all skill levels and no programming, statistical, or computer science backgrounds are necessary. We offer these services in the form of workshops, one-to-one consulting, and working groups that cover a variety of research topics, digital tools, and programming languages.  

Visit the [D-Lab homepage](https://dlab.berkeley.edu/) to learn more about us. You can view our [calendar](https://dlab.berkeley.edu/events/calendar) for upcoming events, learn about how to utilize our [consulting](https://dlab.berkeley.edu/consulting) and [data](https://dlab.berkeley.edu/data) services, and check out upcoming [workshops](https://dlab.berkeley.edu/events/workshops).

# Other D-Lab Python Workshops

Here are other Python workshops offered by the D-Lab:

### Basic competency

* [Python Fundamentals](https://github.com/dlab-berkeley/python-fundamentals)
* [Python Data Wrangling](https://github.com/dlab-berkeley/Python-Data-Wrangling)
* [Python Geospatial Fundamentals](https://github.com/dlab-berkeley/Python-Geospatial-Fundamentals)
