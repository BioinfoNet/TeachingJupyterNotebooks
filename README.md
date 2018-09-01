
# TeachingJupyterNotebooks

This repository contains resources for the Open Science workshop for teaching about jupyter
notebooks. 

---

## Quick Introduction to Jupyter Notebooks

Throughout this workshop, we will be using Jupyter Notebooks. Although the vlabs's available you will be using will have Jupyter setup, these notes are provided for you want to set it up in your computer. 

### Introduction
The Jupyter Notebook is an interactive computing environment that enables users to author notebooks, which contain a complete and self-contained record of a computation. These notebooks can be shared more efficiently. The notebooks may contain:

* Live code
* Interactive widgets
* Plots
* Narrative text
* Equations
* Images
* Video

It is good to note that "Jupyter" is a loose acronym meaning Julia, Python, and R; the primary languages supported by Jupyter. However, other languages are supported by Jupyter.

The notebook can allow a computational researcher to create reproducible documentation of their research. As Bioinformatics is datacentric, use of Jupyter Notebooks increases research transparency, hence promoting open science. 


### Setting Up
* Clone this repository to your working directory. 

    `git clone https://github.com/BioinfoNet/TeachingJupyterNotebooks.git`
    
* Download Anaconda for your operating system for Python 3. Use this [link](https://www.anaconda.com/download/)

* Follow the install instructions for your operating system. [Here are the instructions](https://conda.io/docs/user-guide/install/index.html).

* Afterwards, navigate to the directory where the folder is using `cd` and `ls`. Then run this command in your terminal 

    `conda env create -f environment.yml`

This will create an environment called jupyter-notebook-tutorial. You can activate it  like this

    `source activate jupyter-notebook-tutorial`

* In your terminal, in the directory where you cloned this repository. Run this command

    `jupyter notebook jupyter-notebook-slides.ipynb`
    
Alternatively, let's get packages which will enable you to use the tools that are demonstrated.

* Open your terminal. Type this command to get Nbextensions

    `pip install jupyter_contrib_nbextensions`
    
    `jupyter-contrib nbextension install --sys-prefix`

* Now to get the interactive dataframe tool called qgrid

	`pip install qgrid`

* You can also search github to figure out what you've installed does for instance,
here's the repository for jupyter themes https://github.com/dunovank/jupyter-themes, Nbextensions
https://github.com/ipython-contrib/jupyter_contrib_nbextensions and qgrid https://github.com/quantopian/qgrid.
Additionally, these were covered during the presentation.
	
* Then get bioconda. This avails tools commonly used for bioinformatics e.g samtools,
bowtie and bwa. Follow the steps in this [link](https://bioconda.github.io/)
    
    
* To get tools specifically for bioinformatics. Get scikit-bio 
	
	`pip install scikit-bio`


---

## Project Structure

The repository has a number of files that constitute elements of the jupyter notebook. 
They include:

- `README.md` : Markdown text with an explanation of how the user can make use of these resources. 

- `environment.yml`: Has instructions to create the same environment the creator has in your
own system.

- `jupyter-notebook-slides.ipynb`: Contains the presentation that shows the reader how to use
notebooks with bioinformatic examples mostly. If you're having problems starting up this notebook, try opening 
`jupyter-notebook-slides2.ipynb`

- `files:` Has a variety of files from notebooks, fasta, fastq files among other files.

- `storeddf.ipynb`: Contains created dataframes of counts of specific bases of several microbes 16S rRNA gene.  


## Further Reading
This was a quick introduction. To learn more about Jupyter notebooks, and what you can do with it, check the following resources:
- [Jupyter Notebook Tutorial: The Definitive Guide](https://www.datacamp.com/community/tutorials/tutorial-jupyter-notebook)
- [Jupyter Documentation](http://jupyter-notebook-beginner-guide.readthedocs.io/en/latest/)
- [Jupyter Notebook for Beginners: A Tutorial](https://www.dataquest.io/blog/jupyter-notebook-tutorial/)

