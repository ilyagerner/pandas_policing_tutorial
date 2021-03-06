# Dive Into Exploratory Data Analysis with Python & Pandas
Exploratory data analysis using Python, Pandas and data from the Stanford Open Policing Project.

![Meme](https://i.imgflip.com/2xhjll.jpg)

## What are we going to cover?
Rather than focus on statistical rigour, we'll first work through the practical aspects of data wrangling in Python. Then we'll discuss some of the pitfalls inherent in trying to draw conclusions from the messy world. All through out, we'll be working with a dataset that's relevant to anyone concerned about justice, public safety, and racial equality.

## What dataset are we using?
We'll be using a modified version of the Maryland subset of the [Stanford Open Policing Project](https://openpolicing.stanford.edu) dataset, made available under the Open Data Commons Attribution License.

## How do I download the dataset and the associated jupyter notebooks?
There are two equally valid ways to get the data:

- If you're comfortable with git, you can click the green button above and clone the repository:
```
git clone https://github.com/ilyagerner/pandas.git
```
- Otherwise you can click the green button above and download the repository as a ZIP archive.
- Be sure to unzip the dataset into the same folder as the Jupyter workbook.

## What Python packages do I need to have installed?

We'll be using the following:
- Python 3.7.3 (but we're unlikely to use any of the newest features, so older versions should work fine)
- pandas
- numpy
- matplotlib*
- seaborn*
- altair*

*the graphing libraries are only necessary for a couple lines of code. 
They may be installed with [Pipenv](http://pipenv.org/).

A good way to avoid the unpleasant scenario outlined in the XKCD comic is to rely on the Anaconda distribution for your data science libraries. This is less vital for Mac and Linux users, but important for Windows users thanks to the various C and FORTRAN dependencies in the Python data stack.

### Instructions for Installing Anaconda
1. Download the appropriate version of [Anaconda](https://www.anaconda.com/distribution/#download-section)
2. Follow the instructions on that page to run the installer
3. Test out the jupyter notebook: open a Terminal window (on Mac or Linux), navigate to the directory where you have downloaded the dataset/workshop notebook and type:
`
jupyter notebook
`
3. On Windows, start the Anaconda launcher, which you can find in C:\Anaconda or, in the Start menu. Start the jupyter notebook by typing `jupyter notebook`. A new browser window should open.

## Who led the workshop and is there a way to contact him??
Ilya Gerner can be found on twitter as [@igerner](https://twitter.com/igerner) and via email at ilyagerner@gmail.com.
