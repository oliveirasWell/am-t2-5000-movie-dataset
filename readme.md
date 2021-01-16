# Clustering with K-Means, Mini Batch K-Means and DBSCAN

This project is a notebook about the [TMDB 5000 Movie Dataset](https://www.kaggle.com/tmdb/tmdb-movie-metadata) and propose three clustering models using, respectively, K-Means, Mini Batch K-Means and DBSCAN.

This dataset includes a list of 5000 movies with information of name, genre and other movie information extracted from the imdb. 

The dataset common:

```
homepage

id

original_title

overview

popularity

production_companies

production_countries

release_date

spoken_languages

status

tagline

vote_average

Lost columns:

actor1facebook_likes

actor2facebook_likes

actor3facebook_likes

aspect_ratio

casttotalfacebook_likes

color

content_rating

directorfacebooklikes

facenumberinposter

moviefacebooklikes

movieimdblink

numcriticfor_reviews

numuserfor_reviews
```

First we create new columns and refactor some others, to use PCA to create an 2-dimensional dataset, which is possible to plot and visualize the clustering separately.

In this jupyter notebook we execute some experiments and compare with silhouette_avg metric.

## Requirements

 - [Anaconda](https://docs.anaconda.com/anaconda/install/)
 - [Jupyter Notebook](https://jupyter.org/install)

## Install environment

- Install all requirements and active the conda environment.

```shellscript
conda env create -f environment.yml
conda activate am-t1-credit-card-fraud-detection //name of my last project
```

## Running

`jupyter notebook main.ipynb`


