
# Programming and Data Analysis for Modern Neuroscience
NEU 365P/385L - Spring 2023

# Table of Contents
- [Course Objective](#course-objective)
    - [Breadth over Depth](#breadth-over-depth)
    - [Concept before Math](#concept-before-math)
- [Course Policies](#course-policies)
    - [Prerequisites](#prerequisites)
    - [Requirements](#requirements)
    - [Inclusion](#inclusion)
    - [Academic Integrity](#academic-integrity)
    - [Accomodations](#accomodations)
    - [Contact](#contact)
    - [Office Hours](#office-hours)
    - [Attendance](#attendance)
    - [Grading](#grading)
    - [Grading Rubric](#grading-rubric)
- [Discussion Board](#discussion-board)
- [Programming Rules of Thumb](#programming-rules-of-thumb)
- [Syllabus](#syllabus)
- [Setup your Python environment](#setup-your-python-environment)

# Course Objective
*The ability to read and write are obvious fundamental skills critical to all academic and quantitative pursuits.* **Fast approaching this level of fundamental importance is the ability to write computer programs to analyze and manipulate data sets ever increasing in richness and size.** This skillset is necessary to work with a wide array of systems whose models and behavior are sufficiently complex to make analysis by hand intractable.

**In this course you will translate problems into code applying modern approaches for data analysis, statistical inference and modeling to various levels of neural systems and their component behavior.** We will use Python as a coding environment, and you will be exposed to resources and options for scientific computing.

 *Although geared for neuroscience, the approaches covered in this course are highly salient for a wide array of applications.*

## Breadth over Depth
We will cover a wide array of topics rather than explore any one topic in great detail (see [Syllabus](#syllabus)). Topics will be introduced at a level where you should be able to understand each concept and put them to use. However, realize up front that we may have only scratched the surface.

*The goal of the course is to give you enough of a basic toolset that you will have the necessary foundation to develop programs for any concept that you understand.*

## Concept before Math
It is my opinion that in many cases it is advantageous to first gain a conceptual understanding for an analytical method prior to attempting to fully understand all of the underlying math. In this course we will leverage computational resources that enable you to quickly apply and gain a working understanding of many data analysis techniques without having to fully understand their complete mathematical basis.

This is not to say that the math is unimportant, but rather that your goal in this course will be both a conceptual understanding and practical working ability to utilize the approaches discussed. I leave it to you to gain a more complete mathematical understanding of those approaches you are interested in using outside of this course (*which you should do*). To that end, the working and conceptual understanding you gain here should make this a much easier task.

Finally, it is impossible to avoid math entirely when discussing data analysis techniques. I will endevour to keep the math as basic as possible and focus on the concepts.

# Course Policies
## Prerequisites
There are no prerequisites for this course. *However, you are expected to be familiar with basic mathematical functions and concepts, and you will be asked to perform quantitative calculations and to think critically.* **This is NOT an easy course.**

## Requirements
- You must **bring a laptop to class** for hands on participation. If you do not own a laptop, contact your department or the College of Natural Sciences to obtain a loaner for the duration of the course.
- You should:
    - be motivated
    - **be prepared to work hard**
    - be respectful
    - **help to foster an inclusive environment**
    - have fun!

## Inclusion
Along with the entire Department of Neuroscience, this course embraces a notion of an intellectual community enriched and enhanced by diversity along a number of dimensions, including race, ethnicity and national origins, gender and gender identity, sexuality, class, ability level, and religion. We are especially committed to fostering an environment where you feel heard and respected in your courses.

## Academic Integrity
It is perfectly fine to work with your fellow students or anyone else on the homework assignments. If you do so, **you must include a note on your assignment indicating with whom you collaborated**. Any academic dishonesty such as copying a fellow students assignment without collaborating in its completion will be severly punished as outlined by the University. **Most importantly, the ability to solve problems such as those in the homeworks is exactly the skillset you are here to obtain.**

## Accomodations
Students with disabilities may request appropriate academic accommodations from the Division of Diversity and Community Engagement, [Services for Students with Disabilities](http://www.utexas.edu/diversity/ddce/ssd/) (471-6259). 

## Contact
Please contact myself or the TA via **Canvas**.

## Office Hours
Office hours will be both in person and over Zoom, so you can attend as you see fit. The Zoom link for office hours will be posted on **Canvas**.

## Attendance
You are expected to attend all classes. **In-class quizzes cannot be made up.** If you have to miss a class, you must inform me as far ahead of time as is possible.

## Grading
Your grade is determined by your cumulative points total from **attendance**, **homework**, and in-class **quizes**.
```
A: 90-100%
B: 80-89%
C: 70-79%
D: 60-69%
F: <60%
```
Depending on the distribution of scores, I may alter the above ranges to normalize to the difficulty of the assignments. If I do so, **any alteration will only be favorable to you and never unfavorable**. Note that in the case that I do change the ranges, *I will NOT apply a curve to the letter grades*. **I am very happy to give everyone an A if possible.**

## Grading Rubric
Most questions will be worth 3 pts for which the grading rubric is:
```
+1 pt for a remotely valid attempt
+2 pts if there are only minor mistakes
+3 pts if appropriately addressed
```

# Discussion Board
See **Canvas** for a link to the discussion board.

RULES:
- Your identifier MUST BE YOUR NAME if you want to receive extra credit for your participation (see below).
- Be *respectful and inclusive*.
- Do NOT be afraid to *ask questions*.
- You may post code snippets that help to illustrate or answer a question, but do NOT post complete answers to the homework.

You will receive **EXTRA CREDIT for participating** in the course discussion board. Each post that we deem appropriate (I realize this is subjective) will be worth 1 pt of extra credit up to a max of 3 pts per week. For example, *asking or answering a question* are both worth 1 pt each. You can also receive 1 pt for posting a *link to a relevant resource*, but you need to describe the relevance in your post.

# Programming Rules of Thumb
*Being good at programming is NOT simply knowing a lot of program syntax.*

It is about:

- Understanding a problem conceptually and being able to translate it into code.
- Thinking of new ways to tackle a problem and knowing what tools to use.
- Knowing how to fix your program when it does not work.
- Writing a program that is fast enough, not the fastest possible.
- Writing a program that can be understood by other people (or by yourself in a year!)

# Syllabus
**!!! WARNING !!!** *The syllabus is subject to change as the course progresses depending on my judgement.* This is because I modify my course every year to make it that much better for you. That said, the current syllabus is at least a reasonable approximation of what the final course will look like.

- Jan 10 T - [Python environment](/python-setup.md) & [Python basic syntax 1](/python-basics-1.ipynb), HW: [basics]()
- Jan 12 R - [Python basic syntax 2](/python-basics-2.ipynb), HW: [list slicing & iteration]()
- Jan 17 T - [Multi-dimensional data arrays](), HW: [numpy arrays]()
- Jan 19 R - [Data visualization]() & [Random walk lab](), HW: [random walk simulation]()
- Jan 24 T - [Probability distributions of random variables](), HW: [probability distributions]()
- Jan 26 R - [Optimization & Maximum Likelihood Estimation (MLE)](), HW: [MLE]()
- Jan 31 T - [Hypothesis testing]() & [Statistical rigor](), HW: [p-values & effect sizes]()
- Feb 02 R - [Bootstrap]() & [Permutation test](), HW: [bootstrap & permutation test]()
- Feb 07 T - [Numba]() & [Python basic syntax 3](/python-basics-3.ipynb), HW: [numba]()
- Feb 09 R - [Convolution](), [Sequence data & sampling artifacts](), HW: [convolution & filtering]()
- Feb 14 T - [Leaky Integrate & Fire (LIF) neuron](), HW: [LIF neuron simulation]()
- Feb 16 R - [Hidden Markov Model (HMM) for ion channel](), HW: [ion channel HMM]()
- Feb 21 T - [HMM for DNA sequence](), HW: [nucleotide sequence HMM]()
- Feb 23 R - VIDEO ONLY - [Data tables](), HW: [pandas dataframes]()
- Feb 28 T - [Linear regression](), HW: [linear regression]()
- Mar 02 R - [Polynomial & K-Nearest Neighbors (KNN) regression](), HW: [polynomial & KNN regression]()
- Mar 07 T - [Bias/Variance tradeoff](), [Train/Test split]() & [Cross validation](), HW: [cross validation]()
- Mar 09 R - [Regularization](), HW: [ridge & lasso regularization]()
- Mar 14 T - SPRING BREAK
- Mar 16 R - SPRING BREAK
- Mar 21 T - [Generalized Linear Model (GLM): Poisson & Logistic regression](), HW: [Poisson GLM for spiking neuron]()
- Mar 23 R - [Classification, confusion matrix, ROC curve](), HW: [logistic regression classifier]()
- Mar 28 T - [Support Vector Machine (SVM) classifier](), HW: [SVM classifier]()
- Mar 30 R - [Random forest (bagging) & XGBoost (boosting) classifiers](), HW: [random forest classifier]()
- Apr 04 T - VIDEO ONLY - [Clustering](), HW: [GMM clustering]()
- Apr 06 R - [Principal Component Analysis (PCA)](), HW: [PCA]()
- Apr 11 T - [RNAseq lab](), HW: [PCA]()
- Apr 13 R - [Neural Network (NN)](), HW: [NN]()
- Apr 18 T - [Convolutional Neural Network (CNN)](), HW: [CNN]()
- Apr 20 R - [Long/Short Term Memory (LSTM) Recurrent Neural Networks (RNN)]()

# Setup your Python environment
## 1. Install Conda
Download and install the latest version of [Miniconda3](https://docs.conda.io/en/latest/miniconda.html).

## 2. Configure Conda
Conda groups collections of packages into [channels](https://docs.conda.io/projects/conda/en/latest/user-guide/concepts/channels.html). Most of the packages that you will install for this course will come from either the defaults or [conda-forge](https://conda-forge.org/docs/user/introduction.html) channels. Conda only searches channels that you tell it to. To setup conda so that it automatically searches the [conda-forge](https://conda-forge.org/docs/user/introduction.html) channel before searching the defaults channel, open a cmd shell or terminal and run:
```
conda config --add channels conda-forge
```
To see a list of all of the channels that conda will search (top = highest priority, bottom = lowest priority):
```
conda config --show channels
```
Note that this configuration is optional. You can always specify the channel to search when installing packages on a per package basis. An example of this is shown in the next step.

## 3. Create a sandboxed Python environment for this course
In a cmd shell or terminal run:
```
conda create -n neu365p
conda activate neu365p
conda install python
conda install jupyterlab -c conda-forge
```
This does four things:

1. Creates a new conda environemnt named "neu365p".
2. Sets "neu365p" as the active environment for all conda commands.
3. Installs the latest version of the `python` package (from the defaults channel) into the "neu365p" environment.
4. Installs the latest version of the `jupyterlab` package (from the conda-forge channel) into the "neu365p" environment.

*Note that if you configured conda to automatically search the conda-forge channel, then you could omit the `-c conda-forge` portion of the last command.*

**!!!** Note that each time you open a new cmd shell or terminal, you will need to activate the conda environment that you want to use:
```
conda activate neu365p
```
The currently active environment should be displayed in your command prompt, e.g. `(neu365p)`.

You can see a list of all your conda environments with:
```
conda env list
```

## 4. Open JupyterLab
JupyterLab is a complete Python coding user interface that supports Jupyter notebooks (which we will use in this course). It runs in a tab in your browser.

In a cmd shell or terminal run:
```
conda activate neu365p
jupyter-lab
```
This activates your neu365p conda environment (you can omit this if it is already active) and runs JupyterLab from the neu365p environment. **JupyterLab will open up a tab in your browser with a complete user interface** for writing and running Python code.

When you are done using JupyterLab, from within the JupyterLab browser interface select `File->Shutdown`.

## 5. `OPTIONAL:` Install Visual Studio Code (VSCode)
There are a variety of user interfaces for Python coding from the most basic text editor and cmd shell to more complex user interfaces with more features such as JupyterLab. One alternative to JupyterLab that is compatible with Jupyter notebooks is VSCode.
1. Download [Visual Studio Code (VSCode)](https://code.visualstudio.com/)
2. Open VSCode and install the **Python** and **Jupyter** extensions.
3. In VSCode, Select `View->Command Palette...` and search for and select `Python: Select Interpreter`, then select the Python version associated with your neu365p environment (e.g., `Python 3.11.0 ('neu365p')`).
4. In VSCode you can also set the Python interpreter for each individual file. When you open a Python file the interpreter will be displayed in one of the corners. Make sure it is set to the Python version associated with neu365p, otherwise click the displayed interpreter and select from the dropdown the one for neu365p.

*It does NOT matter which user interface you use.* Both JupyterLab and VSCode will give you a pretty similar experience.
