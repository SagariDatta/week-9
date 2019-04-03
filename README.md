# Week 9<br>Clustering Analysis in Python

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/MUSA-620-Spring-2019/week-9/master?filepath=lecture-9.ipynb)

## Updating your local environment

There is one new package we'll need this week so we'll need
to update your Python environment. 

### Option 1
From the Anaconda Prompt or Terminal, run

```
conda activate musa-620
conda install -c conda-forge scikit-learn
```

### Option 2
The `environment.yml` in this repository
contains all of the necessary packages. To update your local environment:

**Step 1.** Download the `environment.yml` file in this repository to your computer.

**Important:** Make sure you download the **raw** version of the file from GitHub and that the file extension on your computer is `.yml`.

**Step 2.** From either the Anaconda Prompt (Windows) or Terminal app (MacOS):

```
conda env update --file environment.yml --name musa-620
```

where `musa-620` should be the same name of the environment you have been using.

## Reference

- scikit-learn
  - [Documentation](https://scikit-learn.org/stable/)
  - [Clustering home page](https://scikit-learn.org/stable/modules/clustering.html#clustering)
  - [K-Means](https://scikit-learn.org/stable/modules/clustering.html#k-means)
  - [DBSCAN](https://scikit-learn.org/stable/modules/clustering.html#dbscan)
- [Andrew Ng's K-means Clustering Lecture](https://www.youtube.com/watch?v=hDmNF9JG3lo&feature=youtu.be)
- [Clustering comparison chart](https://scikit-learn.org/stable/modules/clustering.html#overview-of-clustering-methods)
- [Gapminder Data](https://www.gapminder.org/data/)
- Airbnb
  - [Tom Slee](http://tomslee.net/airbnb-data)
  - [Inside Airbnb](http://insideairbnb.com/get-the-data.html)
