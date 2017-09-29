
# Frequencies of words in novels: a Data Science pipeline

with DataCamp's very own Hugo Bowne-Anderson

## Description

<p align="center">
<img src="img/fb_live_schematic.png" width="550">
</p>

In this live code-along session, you'll learn how to build a Data Science pipeline to plot frequency histograms of words in *Moby Dick*, among many other novels.
We won't give you the novels: you'll learn to scrape them from the website [Project Gutenberg](https://www.gutenberg.org/) (large corpus of books) using the Python package `requests` and how
to extract the novels from this web data using `BeautifulSoup`. Then you'll dive in to analyzing the novels using the Natural Language ToolKit (`nltk`).
In the process you'll learn about important aspects of Natural Language Processing (NLP) such as tokenization and stopwords.
You'll come out being able to visualize word frequency histograms of any novel that you can find on Project Gutenberg.
The NLP skills you develop, however, will be applicable to much of the data that Data Scientists encounter as the vast proportion of the world's data is unstructured data and includes a great deal of text.

For example, what would the following word frequency histogram be from?

<p align="center">
<img src="img/d-x.png" width="450">
</p>

## Prerequisites

Not a lot. It would help if you knew 

* programming fundamentals and the basics of the Python programming language (e.g., variables, for loops);
* a bit about Jupyter Notebooks;
* your way around the terminal/shell.


**However, I have always found that the most important and beneficial prerequisite is a will to learn new things so if you have this quality, you'll definitely get something out of this code-along session.**

Also, if you'd like to watch and **not** code along, you'll also have a great time and these notebooks will be downloadable afterwards also.

If you are going to code along and use the [Anaconda distribution](https://www.anaconda.com/download/) of Python 3 (see below), I ask that you install it before the session.


## Getting set up computationally

### 1. Clone the repository

To get set up for this live coding session, clone this repository. You can do so by executing the following in your terminal:

```
git clone https://github.com/datacamp/datacamp_facebook_live_nlp
```

Alternatively, you can download the zip file of the repository at the top of the main page of the repository. If you prefer not to use git or don't have experience with it, this a good option.

### 2. Download Anaconda (if you haven't already)

If you do not already have the [Anaconda distribution](https://www.anaconda.com/download/) of Python 3, go get it (n.b., you can also do this w/out Anaconda using `pip` to install the required packages, however Anaconda is great for Data Science and I encourage you to use it).

### 3. Create your conda environment for this session

Navigate to the relevant directory `datacamp_facebook_live_nlp` and install required packages in a new conda environment:

```
conda env create -f environment.yml
```

This will create a new environment called fb_live_nlp. To activate the environment, execute

```
source activate fb_live_nlp
```

### 4. Open your Jupyter notebook

In the terminal, execute `jupyter notebook`. 

Then open the notebook `NLP_FB_live_coding.ipynb` and we're ready to get coding. Enjoy.


### Code
The code in this repository is released under the [MIT license](LICENSE). Read more at the [Open Source Initiative](https://opensource.org/licenses/MIT). All text remains the Intellectual Property of DataCamp. If you wish to reuse, adapt or remix, get in touch with me at hugo at datacamp com to request permission.
