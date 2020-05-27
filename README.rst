Building your first machine learning in Python
===============================================

Welcome to this tutorial, in this tutorial you'll learn how to use Python
to train a machine learning model. 

Summary
--------
**Duration**: 60 minutes

**Type**: Presentation and labs

In this workshop you'll learn how to use scikit-learn and Python to train a 
basic machine learning model. You'll also learn how to validate and explain
the model to a non-technical audience.

This workshop uses the UCI credit card defaulters dataset. In this workshop 
you'll use this dataset to train a classifier that predicts whether someone's 
going to default his/her credit card payment next month.

System requirements
--------------------
For this tutorial you'll need to have the following tools installed on your 
machine:

* `Python 3.7`_
* `Visual Studio Code`_

This tutorial is designed to work on Linux, Mac, and Windows. Please follow
the installation instructions on the respective product pages to get started.

Getting started
----------------
Follow these steps to get started with the tutorial:

* :code:`git clone https://github.com/wmeints/creditcard-defaulters`
* :code:`cd creditcard-defaulters`
* :code:`pip install -r requirements.txt`
* :code:`code .`

After you've cloned the repo and installed the dependencies, you're ready
to get started. Please read through the next section for the tutorial modules.

Tutorial modules
-----------------
This tutorial contains the following modules:

* `notebooks/01-prepare-data.ipynb`_: In this module we're going to take a look 
  at the data and prepare a training and testing dataset for the machine 
  learning algorithm.
* `notebooks/02-train-model.ipynb`_: In this module we're going to use the 
  prepared data to train a machine learning model that is going to predict 
  whether someone is going to miss a credit card payment next month. We'll 
  also take a look at validating the model's performance.
* `notebooks/03-create-explainer.ipynb`_: In this final module we'll explore 
  explainers and how they help you get a better understanding of why the model 
  is making certain predictions.

To start a module, open the corresponding notebook in Visual Studio Code. 
Each notebook contains explanations and instructions for that part of the 
tutorial.

.. _`notebooks/01-prepare-data.ipynb`: notebooks/01-prepare-data.ipynb
.. _`notebooks/02-train-model.ipynb`: notebooks/02-train-model.ipynb
.. _`notebooks/03-create-explainer.ipynb`: notebooks/03-create-explainer.ipynb
.. _`Visual Studio Code`: https://code.visualstudio.com/
.. _`Python 3.7`: https://www.anaconda.com/products/individual