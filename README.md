# Introduction to Uncertainty Quantification

This version of the course is being taught at Purdue University during Spring 2018.
The code for the course is ME 59700 and MA 598.
The instructor is Prof. [Ilias Bilionis](http://www.predictivesciencelab.org/people.html).
The class meets every Tuesday and Thursday 12:00pm-1:15pm at GRIS 102.

The goal of this course is to introduce the fundamentals of uncertainty quantification to advanced undergraduates or graduate engineering and science students with research interests in the field of predictive modeling. Upon completion of this course the students should be able to:

+ Represent mathematically the uncertainty in the parameters of physical models.
+ Propagate parametric uncertainty through physical models to quantify the induced uncertainty on quantities of interest.
+ Calibrate the uncertain parameters of physical models using experimental data.
+ Combine multiple sources of information to enhance the predictive capabilities of models.
+ Pose and solve design optimization problems under uncertainty involving expensive computer simulations.

## Student Evaluation

+ 10% Participation
+ 60% Homework
+ 30% Final Project

## Lectures

+ Lecture 1 - Introduction, 01/09/2018.
  
  - Topics: Course logistics.
  - [Notebook](handouts/handout_01.ipynb)
  - [Slides](https://piazza.com/class_profile/get_resource/jbozz0zxpftby/jc5ad23r6uy2x4)
  
+ Lecture 2 - Quantifying Uncertainties in Physical Models, 01/11/2018.

  - Topics: Scope of UQ; Aleatoric vs epistemic uncertainties; Uncertainty propagation problem; Hands-on example.
  - [Notebook](handouts/handout_02.ipynb)
  - [Slides](https://piazza.com/class_profile/get_resource/jbozz0zxpftby/jc5fvaa8ic74uf)

+ Lecture 3 - Introcution to Probability Theory (Part I), 01/16/2018.

  - Topics: Dynamics of coin toss; Interpretation of probability; Basic rules of probability; Practice examples; Probability as an extension of Aristotelian logic.
  - [Notebook](handouts/handout_03.ipynb)
  - [Slides](https://piazza.com/class_profile/get_resource/jbozz0zxpftby/jc8azrf8f3x3a)
  
+ Lecture 4 - Introduction to Probability Theory (Part II), 01/18/2018.

  - Topics: Independence; Conditional independence; Graphical representation of probability models; Causality; Discrete random variables; Continuous random variables; Expectations.
  - [Notebook](...)
  - [Slides](...)
  
+ Lecture 5 - Common Random Variables, 01/23/2018.

  - Topics: Uniform distribution; Generating uniform random numbers; Bernoulli distribution and how to sample it; Binomial distribution; Poisson distribution.
  - [Notebook](...)
  - [Slides](...)
  
+ Lecture 6 - Turning Prior Information to Probability Statements, 01/25/2018.

  - Topics: Principle of insufficient reason, maximum entropy principle, statistical mechanics.
  - [Notebook](...)
  - [Slides](...)
  
+ Lecture 7 - Bayesian Parameter Estimation, 01/30/2018.

  - Topics: Maximum likelihood; maximum a posteriori estimates; generalized linear regression; the evidence approximation; automatic relevance determination.
  - [Notebook](...)
  - [Slides](...)

+ Lecture 8 - Priors on Function Spaces, 02/01/2018.

  - Topics: Random fields, Gaussian random fields (Gaussian processes)
  - [Notebook](...)
  - [Slides](...)
  
+ Lecture 9 - Conditioning a Random Field on Observations, 02/06/2018.

  - Topics: Gaussian process regression
  - [Notebook](...)
  - [Slides](...)
  
+ Lecture 10 - Reducing the Dimensionality of Random Fields, 02/08/2018.

  - Topics: Karhunen-Lo\`eve expansion (KLE); Nystr\"om approximation to the KLE.
  - [Notebook](...)
  - [Slides](...)
   
+ Lecture 11 - Uncertainty Propagation: Sampling Methods I, 02/13/2018.

  - Topics: Monte Carlo; high-dimensional integration; error estimates; convergence; importance sampling.
  - [Notebook](...)
  - [Slides](...)
  
+ Lecture 12 - Uncertainty Propagation: Sampling Methods II, 02/15/2018.

  - Topics: Latin hyper-cube designs; multi-level Monte Carlo.
  - [Notebook](...)
  - [Slides](...)
   
+ Lecture 13 - Uncertainty Propagation: Polynomial Chaos I, 02/20/2018.

  - Topics: Orthogonal polynomials; recursive relations for calculating orthogonal polynomials; solving stochastic ODEs; solving stochastic PDEs;
  - [Notebook](...)
  - [Slides](...)
  
+ Lecture 14 - Uncertainty Propagation: Polynomial Chaos II, 02/22/2018.

  - Topics: The collocation approach; sparse grid collocation; adaptive sparse grid collocation; the curse of dimensionality.
  - [Notebook](...)
  - [Slides](...)
 
+ Lecture 15 - Uncertainty Propagation: Bayesian Approaches & High-dimensions, 02/27/2018.
  
  - Topics: Quantifying epistemic uncertainties induced by limited data; principal component analysis.
  - [Notebook](...)
  - [Slides](...)
  
+ Lecture 16 - Markov Chain Monte Carlo I, 03/01/2018.

  - Topics: Metropolis; Metropolis-Hastings; experessing models in pymc;
  - [Notebook](...)
  - [Slides](...)
  
+ Lecture 17 - Markov Chain Monte Carlo II, 03/06/2018.

  - Topics: Hybrid-Monte Carlo; Delayed rejection adaptive Metropolis.
  - [Notebook](...)
  - [Slides](...)
  
+ Lecture 18 - Bayesian Monte Selection using Sequential Monte Carlo, 03/08/2018.

  - Topics: Hybrid-Monte Carlo; Delayed rejection adaptive Metropolis.
  - [Notebook](...)
  - [Slides](...)
  
+ **No lecture on Tuesday 03/12/2018** (spring break).

+ **No lecture on Thursday 03/15/2018** (spring break).

+ Lecture 19 - Accelerating Bayesian Statistics, 03/20/2018.

  - Topics: Kullback-Leibler divergence; expectation propagation; variational infernece.
  - [Notebook](...)
  - [Slides](...)
  
+ **No lecture on Thursday 03/22/2018** (The instructor will be at [2018 NSF Design Circle Workshop: Designing and Developing Global Engineering Systems](http://blogs.oregonstate.edu/designcircle/)).
  
+ Lecture 20 - Inverse Problems/Model Calibration: Classic Approaches, 03/27/2018.
 
  - Topics: Loss function minimization; Tikhonov regularization.
  - [Notebook](...)
  - [Slides](...)
  
+ Lecture 21 - Inverse Problems/Model Calibration: Bayesian Approaches, 03/29/2018.

  - Topics: stochastic formulation of inverse problems; the Laplace approximation; solving inverse problems with MCMC; hierarchical Bayes modeling.
  - [Notebook](...)
  - [Slides](...)
  
+ Lecture 22 - Inverse Problems/Model Calibration: Selection of Optimal Experiments, 04/03/2018.

  - Topics: expected information gain; optimization of sensor locations; design of experiments;
  - [Notebook](...)
  - [Slides](...)
  
+ Lecture 23 - Posing and Solving Optimization Problems Under Uncertainty, 04/05/2018.

  - Topics: expected utility maximization; multi-objective optimation; risk; min-max approach; soft constraints; sampling average approximation.
  - [Notebook](...)
  - [Slides](...)
  
+ Lecture 24 - Bayesian Algorithms for Solving Stochastic Optimization Problems with Expensive Information Sources, 04/10/2018.

  - Topics: Bayesian global optimization; expected improvement; probability of improvement; knowledge gradient; expected improvement in dominated hypervolume.
  - [Notebook](...)
  - [Slides](...)
  
+ Lecture 25 - Data Assimilation in Dynamical Systems, 04/12/2018.

  - Topics: Kalman filters; ensemble Kalman filters; particle filters.
  - [Notebook](...)
  - [Slides](...)
  
+ **No lecture on Tuesday 04/16/2018** (The instructor will be at the [SIAM Conference for Uncertainty Quantification 2018](https://www.siam.org/meetings/uq18/)).

+ **No lecture on Thursday 04/19/2018** (The instructor will be at the [SIAM Conference for Uncertainty Quantification 2018](https://www.siam.org/meetings/uq18/)).
  
+ Lecture 26 - Multi-fidelity/multi-source information fusion, 04/19/2018.

  - Topics: multi-fidelity Gaussian process regression; multi-output deep neural networks.
  - [Notebook](...)
  - [Slides](...)
  
+ Lecture 27 - Probabilistic Numerics, 04/26/2018.

  - Topics: numerical algorithms as probabilistic inference; quantification of the discretization error in ODEs and PDEs; physical models as information sources.
  - [Notebook](...)
  - [Slides](...)
  

## Homework Notebooks

+ Homework 1 - Probability Theory Basics, due 01/23/2018.

+ Homework 2 - Choosing Prior Probabilities, due 01/30/2018.

+ Homework 3 - Bayesian Parameter Estimation, Gaussian Process Regression, due 02/13/2018.

+ Homework 4 - Uncertainty Propagation: Sampling Techniques, due 02/20/2018.

+ Homework 5 - Uncertainty Propagation: Polynomial Chaos, due 03/01/2018.

+ Homework 6 - Advanced Bayesian Infernece Techniques, due 03/27/2018.

+ Homework 7 - Inverse Problems/Model Calibration, due 04/05/2018.

+ Homework 8 - Optimization Under Unceratinty, due 04/12/2018.



## Installation of Required Software for Viewing the Notebookes

Find and download the right version of 
[Anaconda for Python 2.7](https://www.continuum.io/downloads) from Continuum Analytics.
This package contains most of the software we are going to need.

### OS Specific Instructions

#### Microsoft Windows

+ We need C, C++, Fortran compilers, as well as the Python sources.
Start a command line (look for ``cmd``) and type:
```
conda install mingw libpython
```
+ Finally, you need [git](https://git-scm.com/downloads). As you install it,
make sure you select that you want to use it from the Windows command prompt.

#### Apple OS X

+ Download and install [Xcode](https://developer.apple.com/xcode/download/)
+ Agree to the license of Xcode by opening a terminal and typing:
```
sudo xcrun cc
```
+ Install your favorite version of the GNU compiler suite.
You can do this with [Homebrew](http://brew.sh/) (after you install it of course),
by typing in the terminal:
```
brew install gcc
```
Alternatively, you may use the [MacPorts](https://www.macports.org/).

#### Linux

Nothing special is required.

### Installation of Required Python Packages

Independently of the operating system, use the command line to install the following Python packages:
+ [Seaborn](http://stanford.edu/~mwaskom/software/seaborn/), for beatiful graphics:
```
conda install seaborn
```

+ [PyMC](https://https://github.com/pymc-devs/pymc) for MCMC sampling:
```
conda install pymc
```

+ [GPy](https://github.com/SheffieldML/GPy) for Gaussian process regression:
```
pip install GPy
```

+ [py-design](https://github.com/PredictiveScienceLab/py-design) for generating designs for computer codes:
```
pip install py-design
```

+ [py-orthpol](https://github.com/PredictiveScienceLab/py-orthpol) for generating orthogonal polynomials with respect to arbitrary probability measures:
```
pip install py-orthpol
```

## Running the notebooks

+ Open the command line.
+ `cd` to your favorite folder.
+ Then, type:
```
git clone https://github.com/PredictiveScienceLab/uq-course.git
```
+ This will download the contents of this repository in a folder called `uq-course`.
+ Enter the ``uq-course`` folder:
```
cd uq-course
```
+ Start the jupyter notebook by typing the command:
```
jupyter notebook
```
+ Use the browser to navigate the course, experiment with code etc.
+ If the course contented is updated, type the following command (while being inside `uq-course`) to get the latest version:
```
git pull origin master
```
Keep in mind, that if you have made local changes to the repository, you may have to commit them before moving on.
