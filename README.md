# Introduction to Jupyter

Introduction to Jupyter for the LEADS Summer School 

_May 20, 2021 at 11am ET_

_Instructors: Lindsey Heagy ([@lheagy](https://github.com/lheagy)), Devin Cowan ([@dccowan](https://github.com/dccowan))_

_Slides: http://bit.ly/leads-intro-jupyter_

## Goals
The goals of this tutorial are to:  
- give a picture of the open ecosytem of tools in Jupyter and Python
- introduce some of the common packages for data science in Python
- talk about the practical use of Jupyter and highlight features that are useful in a data science workflow

## Schedule

### Part 1: learn by doing -- working through a motivating example with the Mauna Loa CO2 data set
- [10 min] Introduction: overview of Jupyter and Syzygy, brief overview of Python
- [10 min] Steps for accessing the tutorial notebooks to follow along 
- [30 min] Mauna Loa notebook
    - overview of common packages in Python including Pandas and Matplotlib 
    - features of JupyterLab: notebook, viewing different data types
    - using the notebook: 
        - how to run cells, add cells, change cell type
        - tab completion for exploring name-space
        - accessing documentation using `?` and `??`
    - widgets and rich outputs 
- [10 min] Break + questions

### Part 2: a more detailed overview of Jupyter 
- [10 min] Notebook 2: more details 
    - cell types
    - managing the kernel
    - rich displays & markdown 
- [30 min] Notebook 3: IPython 
    - documentation & getting help 
    - interactive workflow 
    - running shell commands
    - magic functions 
    - debugging in Jupyter
    - quick tour of widgets
- [10 min] tips for reproducible workflows and sharing notebooks on Binder  
- [10 min] Wrap-up, additional resources and questions 

## Following along


### On your own machine 

First, you will need to have downloaded anaconda

Next, if you are familiar with using git, you can clone this repository, but if not, just click on "code" and "download zip." You can then move and unpack the zip file wherever you would like to run it from. You can then open up a terminal / command prompt in that folder and run 

```
jupyter lab
```

### On Syzygy 

Through [PIMS](https://www.pims.math.ca/), [Cybera](https://www.cybera.ca/) and [Compute Canada](https://www.computecanada.ca/), we have access to Jupyter resources on the cloud. You can go to [syzygy.ca](https://syzygy.ca/) to access the hubs. At the top right there is a "Launch" button. If you see your university listed there, you can select it, if not, select the `PIMS (Google)` hub and you can login with a gmail account there. 

Then download this code repository, unzip it, and upload all of the files to the syzygy hub. 

### On mybinder.org

Alternatively, you can run the notebooks through mybinder.org by following the [binder link here](https://mybinder.org/v2/gh/lheagy/leads-intro-jupyter/HEAD?urlpath=lab). Note that this is an ephemeral session and that changes you make here will not be saved. If you would like to save your changes, you can download the notebook.  



