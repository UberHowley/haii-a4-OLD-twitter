# Assignment #4 Setup Instructions

## Step #0 Create a Twitter Developer Account
**DO THIS FIRST!** It may take some time for Twitter to approve you! Read the instructions in Glow and watch the Assignment 4 video for directions on how to do this.

## Step #1 Install Necessary Programming Modules (new!)
This week, in addition to Anaconda Python 3.6 (or greater) with Jupyter Notebooks and pandas, you'll also need to install the `tweepy` and `fastai` modules. For tweepy, you may be able to use the `conda install -c conda-forge tweepy` or possibly the `pip install tweepy` command. If you pip install fastai, you'll need to install `pytorch` first, [according to the fastai installation instructions](https://docs.fast.ai/#Installing). Alternatively, using conda (and on Windows, the conda shell) would be best, as we're using Anaconda python:

```
conda install -c fastai -c pytorch -c anaconda fastai gh anaconda
```

### Using Anaconda
Install Anaconda Python 3.6 (or greater) if you haven't already for our previous assignments. [https://www.anaconda.com/distribution/](https://www.anaconda.com/distribution/) You'll need Jupyter Notebook, and pandas, at the very least.

### Problems with Module Versions, or with Windows machines
If you're using a Windows machine and the above installation instructions don't work, or encountering significant issues with module version and installation, consider using Google Colab to open up this assignment's Jupyter notebook. You can access any public GitHub Jupyter Notebook on Google Colab by replacing the github.com in the URL with colab.research.google.com/github, like so: `https://colab.research.google.com/github/UberHowley/haii-a4/blob/main/Satire_Bot.ipynb`. Make sure you save regularly! When you are reading data in our notebook, you need to copy the “data” folder to some place you can access from Colab. These instructions and more are available via the Video lecture for this assignment.


## Step #2 Download homework files
Download all the files in this repository. Place these files into a well-named folder on your computer, and click on the zip file to unzip the data folder. You will zip all the files in this directory and submit the `.zip` file to Glow when completed.

## Step #3 Open the Jupyter Notebook

### Opening Notebooks: VS Code Option
If you have VS Code, it has built-in support for running Jupyter Notebooks. You'll be prompted to select a Python environment, and should choose the anaconda python environment so you don't have to separately install scikit-learn, pandas, numpy, etc. individually.

### Opening Notebooks: Terminal Option
In your terminal, navigate to your homework folder and run `jupyter notebook .` to start the notebook. A notebook session should open up in your browser.

On a Mac, you can run a Jupyter notebook from Terminal by typing `jupyter notebook name_of_file_here.ipynb`. On Windows, you will do [something similar](https://pythonforundergradengineers.com/opening-a-jupyter-notebook-on-windows.html) but by running the 'Anaconda Prompt' that comes with the Anaconda distribution.

### Opening Notebooks: Anaconda Graphical User Interface Option
Once Anaconda is installed on your machine, open an application called Anaconda-Navigator. On the main page, click the 'launch' button on the Jupyter Notebook tile. A notebook session should open up in your browser.

### Opening Notebooks: Google Colab Option
If you lack space on your machine for installing libraries, Google Colab can be a good option. Google Colab is a cloud-based Jupyter Notebook. Instructions for using Google Colab for this assignment are available on the assignment page.

## Step #4
Once you have the Jupyter Notebook for this assignment open, then follow the instructions described therein. 

# Jupyter Notebooks
If you haven't used Jupyter Notebooks before, a good first step for you would be to read the [Jupyter Notebook Tutorial: The Definitive Guide](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook) and take the User Interface Tour in the Jupyter notebook Help menu once you've opened your first Jupyter Notebook.

# Resources
- General resources: 
    * [Jupyter Notebook Tutorial: The Definitive Guide](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook)
    * [Python3 Documentation](https://docs.python.org/3/index.html) (tutorial and library reference are likely useful)
    * Python tutorials from [w3schools](https://www.w3schools.com/python/) and [Scrimba](https://scrimba.com/learn/python).
    * [Python pandas documentation](https://pandas.pydata.org/pandas-docs/stable/)
    * [A list of python pandas tutorials](https://pandas.pydata.org/pandas-docs/stable/getting_started/tutorials.html)
    * [pandas.series.str.count](https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.Series.str.count.html)
- Fastai:
  * [fastai Language Modeling](https://docs.fast.ai/tutorial.text.html#The-ULMFiT-approach)
  * [fastai help forum](https://forums.fast.ai/)
  * [fastai](https://www.fast.ai/)
- Tweepy:
  * [Twitter Developer Account](https://developer.twitter.com/en)
  * [Tweepy Documentation](https://www.tweepy.org)
  * [Tweepy Getting Started](http://docs.tweepy.org/en/v3.6.0/getting_started.html)
