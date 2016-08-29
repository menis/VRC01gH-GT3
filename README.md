# VRC01gH-GT3  
  
### about  
  
This repository contains code and antibody sequence data from our Cell manuscript: "Tailored immunogens direct affinity maturation toward HIV neutralizing antibodies." 
  
  
### sequences
Sequences described in the manuscript are avalable as FASTA files in the `fastas` directory.
  
  
### getting started  
  
If you just want to see the code and figures, click on `figure_code.ipynb` and Github will render the notebook for you. Although you can't change/run any of the code yourself, you can see the code and the resulting figures.  
  
Actually running the code yourself takes a few more steps. If you're new to Python, a great first step is to install the [Anaconda Python distribution](https://www.continuum.io/downloads), which includes pip as well as a ton of useful scientific Python packages. Unfortunately, because some required Python dependencies are not compatible with Python 3.x, Python 2.7.x is required. Working with GitHub repositories is also much easier if you have [git](https://git-scm.com/) installed.  
  
After you've installed git and Anaconda, you need to clone this repository and install some additional Python dependencies:  
  `git clone https://github.com/briney/VRC01gH-GT3/`  
  `cd VRC01gH-GT3`  
  `pip install -r requirements.txt`  
  
Finally, you need to install [MUSCLE](http://www.drive5.com/muscle/index.htm), which we use to perform multiple sequence alignments.  
  
Now all that's left to do is start Jupyter Notebook, which will open a browser window:  
`jupyter notebook`  
  
Clicking on `figure_code.ipynb` will open a new browser window with the code used to generate most of the panels in Figure 3. All you need to do to run a block of code is to click on the code block and press `Shift-Enter`. It's important to note that some blocks of code depend on the results of previous blocks, so running the blocks in order is best.
