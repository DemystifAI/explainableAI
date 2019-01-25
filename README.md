# explainableAI
## Repository for the Applied Machine Learning Days workshop on explainable AI

Welcome to the Explainable AI Workshop! In this session we will explore some basic concepts of building machine learning models with the additional feature of creating procedures for interpreting models and their features. An important step in explainable AI is to be able to create models that can be interpreted, validated, and verified in a transparent fashion. In order to do this, we've put together some notebooks that will help clarify the process in several steps of introducing some recent tools for building explainable models. 

We will use Jupyter notebooks along with Python 3.6. The easiest way to get a Jupyter notebook session up and running is by using Anaconda which is available for Windows/iOs/Ubunutu. 

### Download Anaconda
Anaconda will enable you to create virtual environments and install packages needed for data science and deep learning. With virtual environments you can install specific package versions for a particular project or a tutorial without worrying about version conflicts.

Download Anaconda for your platform and choose the Python 3.6 version: https://www.anaconda.com/download

By downloading Anaconda, you get conda, Python, Jupyter Notebook and hundreds of other open source packages.

Conda is a package manager to manage virtual environment and install packages. To set up a virtual environment, install packages locally in the environment, and get Jupyter running on the enviornment, we will use the following commands:

```
# update conda in your default environment 
$ conda upgrade conda
$ conda upgrade --all
# create a new environment with conda
$ conda create -n [my-env-name]
# activate the environment you created
$ source activate [my-env-name]
# take a look at the environment you created
$ conda info
$ conda list
# install a package with conda and verify it's installed
$ conda install numpy
$ conda list
# take a look at the list of environments you currently have
$ conda info -e
# remove an environment
$ conda env remove --name [my-env-name]
```
To install the required packages for this session, the easiest way is by using the requirements.txt file in the repository. To do this , enter
```
pip install -r requirements.txt
```
To install Shapley and xgboost, one recommended way is the following:
```
conda config --add channels conda-forge
conda install shapely
conda install py-xgboost
```


Finally, to launch Jupyter notebook
```
# launch the Jupyter Notebook server
$ jupyter notebook
# stop the Jupter Notebook server
Ctrl+C 
```



