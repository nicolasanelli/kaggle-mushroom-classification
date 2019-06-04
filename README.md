# kaggle-mushroom-classification
Safe to eat ou deadly poison? Machine learning fit to identify mushrooms classification by edible or poison

## Structure

### Jupyter Notebook

By easy design and documenting mind, this analysis was made in [Jupyter Notebook](https://jupyter.org/), 
which is "an amazing open-source web application that allows you to create and share documents that contain live code, 
equations, visualizations and narrative text".

** Obs: ** You can see my jupyter notebook on this project out of the box by opening 
the [this](mushroom_classification_predict.ipynb) file.

## Pre requisites

There are many ways of having this enviroment for running this project, I encourage you to 
use [python virtualenv](https://virtualenv.pypa.io/en/latest/) provided by [PIP](https://pypi.org/project/pip/), a 
package installer for python.

## How to play-it

First of all, you will need to create you virtualenv rather in python 3. So once you download 
this project, you can run in project root folder:

```
$ virtualenv --python='/usr/local/bin/python3' .ENV
```

This will create a folder called .ENV with some struct inside it. Once this has been successfully, 
you will need to activate you virtual env. This can be made with following code:

```
$ source .ENV/bin/activate
```

You may note that now your bash has a prefix (probably .ENV). This indicates that you are inside your 
virtualenv profile. You can try run 'python -V'and should get your python 3 version.
Now you need to install the project dependencies, that are stored in requirements.txt file. 
Fortunately, PIP has a command for this kind of files:
```
$ pip install -r requirements.txt
```
Now that all your dependencies have been resolved, you can run this jupyter notebook by running:
```
$ jupyter notebook mushroom_classification_predict.ipynb
```
Now you can play-it on your browser.

## Quiting
For stop running Jupyter, you can press Ctrl+C and YES on terminal. And for quiting your virtualenv you cand type:
```
$ deactivate
```

## Authors

* **Nicolas Anelli** - [Github](https://github.com/NicolasAnelli)
