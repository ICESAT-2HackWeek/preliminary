---

title: "Intro and Preparation for ICESat-2 Hackweek"
teaching: 15
exercises: 0
questions:
- "What is the format of this workshop?"
- "Will my laptop work for this hackathon?"
- "Will I need to learn a specific programming language to participate?"
- "What can I do in advance to prepare?"
objectives:
- "Getting patricipants ready for running code in the cloud and on their local machines during the hackweek."
keypoints:
- "hackweeks combine interactive tutorials with open project time in a shared learning environment"
- "participants will conduct tutorial exercises in a cloud environment"
- "everyone is encouraged to arrive with Python installed on their laptop for the project work"
- "there are several different versions of Python, but we will use Python 3.6 for this hackathon"
- "Conda package manager will be used to install Python and other libraries"

---

Welcome to the Cryospheric Sciences with ICESat-2 hackweek! Hackweeks were originally designed by the University of Washington's [eScience Institute](https://escience.washington.edu/), and they aim to provide a welcoming learning environment where you can learn new software tools, collaborate with colleagues, build community and make progress on specific projects. Our [hackweek model](https://www.pnas.org/content/115/36/8872) is constantly evolving and we invite you actively participate as we experiment with new approaches and ideas.

This preliminary tutorial is one that we would like you to complete before arriving to the hackweek. The purpose is to learn about how we plan to work with various software tools and how you can best prepare for our event. We would like everyone works through this tutorial so that we can make the best use of our time together in person. 

### Overview

Our goal during both the tutorial and project time is to give you direct, hands-on experience using the Python programming language. We have chosen Python because it is free and open source, and has many libraries suitable for efficient manipulation of ICESat-2 data. 

Python software is distributed as a series of *libraries* that are called within your code to perform certain tasks. There are many different collections, or *distributions* of Python software. Generally you install a specific distribution of Python and then add additional libraries as you need them. There are also several different *versions* of Python. The two main versions right now are 2.7 and 3.6. Some libraries only work with specific versions of Python.

So even though Python is one of the most adaptable, easy-to-use software systems, you can see there are still complexities to work out and potential challenges when delivering content to a large group. Therefore we have a number of different ways that we are trying to simplify this process to maximize your learning during the hackweek.

First, we will be using [JupyterHub](https://jupyterhub.readthedocs.io/en/latest/) for our tutorials. JupyterHub is a multi-user Hub that provides multiple instances of the single-user Jupyter notebook server. A Jupyter Notebook is an open-source web application that allows users to create and share documents containing live code, equations, visualizations, and markdown texts. Here's an [overview](https://www.slideshare.net/willingc/jupyterhub-a-thing-explainer-overview?from_action=save) of JupyterHub. Click [here](https://icesat-2hackweek.github.io/preliminary/01-JupyterHub-tutorial/) to try out the JupyterHub deployment we will use during our event. Let us know if on Slack you are having problems with installing Conda.

We also provide instructions for using [Anaconda](https://www.continuum.io), which is our recommended Python distribution, for installing and working with Python on your local computer. We can assist in setting up "conda" environments that will simplify the gathering of Python libraries and version specific to the tutorial you are working on.

### Getting set up with Conda

[**Conda**](http://conda.pydata.org/docs/) is an **open source `package` and `environment` management system for python libraries**. We will be using various
Python libraries with multiple dependencies, so it is critical that you have some sort of 
package management system in place. Conda can be installed in almost any computer.

Here are the system requirements:

- Windows Vista or newer, OS X 10.7+, or Linux (Ubuntu, RedHat and others; CentOS 5+)
- 32-bit or 64-bit
- Minimum 3 GB disk space to download and install.

Click [here](https://icesat-2hackweek.github.io/preliminary/02-conda-tutorial/) to start our Conda tutorial. Let us know if on Slack you are having problems with installing Conda.

### Getting setup with Git

Be sure to arrive at Geohackweek with your own [GitHub](https://github.com/) account. We encourage you to start practicing with Git and GitHub in advance of this event. Our tutorials will follow [this](https://berkeley-stat159-f17.github.io/stat159-f17/lectures/01-git/Git-Tutorial..html) lesson. Additional tutorial content from our past hackweeks is [here](https://geohackweek.github.io/Introductory/03-git-tutorial/).

### Brushing up on Python

Here are some excellent resources we recommend using to brush up on your Python skills in advance of our event:

* [Software carpentry lessons](https://software-carpentry.org/lessons/), especially the [Python tutorial](http://swcarpentry.github.io/python-novice-inflammation/)
* [Python Data Science Handbook](https://github.com/jakevdp/PythonDataScienceHandbook) 
* a collection of a variety of [data science lessons](https://github.com/uwescience/Online-Educational-Resources) developed by the UW eScience Institute


