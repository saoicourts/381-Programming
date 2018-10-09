# Math 381 Programming Introduction

This repository holds the files and instructions you will need to get your computer ready to learn about using Python to solve linear programming problems.

## Our set-up
We will be using Python in a Jupyter notebook as a scripting language and Gurobi as the programming solver. This will allow a user-friendly programming environment that shouldn't be too difficult even for first-time programmers while giving you the power of a state-of-the-art optimizing engine to solve your problems.

## Things to do BEFORE COMING TO LECTURE
1. **Get a (free) Gurobi academic license**
You can [visit this page](http://www.gurobi.com/registration/academic-license-reg) to fill out a form to get your academic license. You will need to create an account using your UW email address and then log in to get your key. **Save this until later.**
1. **Install Anaconda and Python**
*Even if you have Python installed on your computer already*, you will need to install the distribution that comes with Anaconda. This will ensure you have a compatible installation which includes Gurobi and Jupyter and everything else you will need.
    
    Visit [this page](http://www.gurobi.com/downloads/get-anaconda) to see the instructions for your operating system. **Be sure to get the version with Python 3.6**. I will be giving instructions for this version of Python and you will find you get frustrating small errors if you get the wrong version. Follow the instructions to install Anaconda and Gurobi. 
        *It will ask if you want to add the new files to your PATH. You probably want this unless you have a custom Python installation already (in which case you probably know what to do).
        *You do not need to install VSCode that comes bundled with it although I think it's a great IDE. We will be using Jupyter notebooks (which comes bundled with Anaconda).
    
1. **Download these files to your computer**
    If you have `git` installed (if you are not sure, you probably don't) you can clone this repository to your computer by opening a terminal, `cd`ing to your desired directory, then issuing the command `git clone https://github.com/NicoCourts/381-Programming`. This has the slight advantage that when I release more files to this repository you can just issue a `git pull` command to get the updates.
    
    Otherwise you can scroll to the top of the page and select the green **Clone or download** button. Then you can download the included files in a zip file and unzip them to your desired directory.

1. **Run Jupyter to make sure everything is working**
    If you are on **Windows**, search for the anaconda folder in your programs and underneath it you should find Jupyter.
    
    If you are on **Mac or Linux**, open a terminal and issue the command `Jupyter Notebook` in the directory containing these files.
    
    In either case, you can then navigate to the file `Getting-Acquainted.ipynb` and open it up. Inside you will find an introduction to Python (if you need it) as well as some commands that will verify that everything is set up properly.

Come talk to me in office hours if you have trouble with any parts of the above. It is important we resolve your issues *before* our lecture so that you can follow along and learn from doing.
