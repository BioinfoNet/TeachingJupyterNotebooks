# TeachingJupyterNotebooks

This repository contains resource for the Open Science workshop for teaching about jupyter
notebooks. 

---

Setting Up

* Download Anaconda for your operating system for Python 3. Use this [link]()

* Afterwards, navigate to the directory where the folder is using `cd` and `ls`. Then
run this command in your terminal 

`conda env create -f environment.yml`

This will create an environment called jupyter-notebook-tutorial. You can activate it 
like this

`source activate jupyter-notebook-tutorial

* In your terminal, in the directory where you cloned this repository. Run this command

jupyter notebook jupyter-notebook-slides.ipynb

---

Project Structure

The repository has a number of files that constitute elements of the jupyter notebook. 
They include:

README.md : Markdown text with explanation of how the user. 
			
images: Contains pictures that are embedded in the notebook.

environment.yml: Has instructions to create the same environment the creator has in your
own system.
			
jupyter-notebook-slides.ipynb: Contains the presentation that shows the reader how to use
notebooks with bioinformatic examples mostly.

files: Has a variety of files from notebooks, fasta, fastq files among other files.

