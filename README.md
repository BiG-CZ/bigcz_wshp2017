# bigcz_wshp2017

BiG-CZ/ODM2 User Workshop

## "tutorial content"

Jupyter notebooks, data files used in tutorials, other code, etc, will be hosted on the repo https://github.com/BiG-CZ/wshp2017_tutorial_content, "a repo that has the initial environment that each user will have within their jupyterhub environment". See the issues created on that repo for info on where we're at vis a vis JupyterHub and tutorial contents, problems we're addressing, etc


## JupyterHub test setup

- **TO-DO:** "Do you know who has control over the http://bigcz.org domain name? I'm trying to figure out the domain for the jupyterhub. I was thinking http://jupyterhub.bigcz.org?" FOLLOW UP WITH ANTHONY.
- From Emilio to Don: will need instructions you have about how to upload notebooks, data, etc (I have some memory of the shell git clone process used in Geohackweek).
- More details, for now, at https://github.com/BiG-CZ/wshp2017_tutorial_content/issues/3
- [JupyterHub tutorial from Geohackweek 2017](https://geohackweek.github.io/Introductory/05-Jupyter-tutorial/)


## ODM2 Jupyter Notebooks

From May 2017 presentation/demo. Hosted on HydroShare, uploaded here as a temporary convenience
- [ODM2 IPython Notebook Examples](https://www.hydroshare.org/resource/ff79d7926f6040c9acd004636b4e4d38/)
  1. [ODM2_Example1.ipynb:](http://nbviewer.jupyter.org/urls/www.hydroshare.org/django_irods/download/ff79d7926f6040c9acd004636b4e4d38/data/contents/ODM2_Example1.ipynb) Create a blank ODM2 database and load controlled vocabulary terms from http://vocabulary.odm2.org in preparation for data loading.
  2. [ODM2_Example2.ipynb:](http://nbviewer.jupyter.org/urls/www.hydroshare.org/django_irods/download/ff79d7926f6040c9acd004636b4e4d38/data/contents/ODM2_Example2.ipynb) Parse water quality sample data from an ODM2 Excel Template file using the ODM2 Python API and write data to an ODM2 database instance and a YAML Observations Data Archive (YODA) file.
  3. [ODM2_Example3.ipynb:](http://nbviewer.jupyter.org/urls/www.hydroshare.org/django_irods/download/ff79d7926f6040c9acd004636b4e4d38/data/contents/ODM2_Example3.ipynb) Read water quality sample data from an ODM2 database instance using the ODM2 Python API for manipulation or visualization of the data. 
- [ODM2: An Information Model and Software Ecosystem for Spatially-Discrete Earth Observations](https://www.hydroshare.org/resource/95458e53fe7e474f85642d6a711729b6/) (Powerpoint)

## R

- [Ben Crary's](https://github.com/benjamincrary) Jupyter Notebook in R, that uses HISCentral & WOFpy, via the WaterML R package: [EnviroDIY_Rnotebook.ipynb](https://github.com/BiG-CZ/BiG-CZ-Toolbox/blob/master/ipynotebooks/EnviroDIY_Rnotebook.ipynb)
- [Dylan Beaudette's (et al)](https://github.com/dylanbeaudette) "NCSS-Tech" [R packages for soil data](http://ncss-tech.github.io/AQP/), including Algorithms for Quantitative Pedology (`AQP`) and `soilDB`
- Look into using [Feather](https://github.com/wesm/feather) as common data-frame binary storage format for two-way exchange/interoperability between R and Python-Pandas (see also this [2016 article about feathers](http://blog.cloudera.com/blog/2016/03/feather-a-fast-on-disk-format-for-data-frames-for-r-and-python-powered-by-apache-arrow/)).

## Introductions to git and conda

- Nice and tested resources from the [UW GeoHackweek](https://geohackweek.github.io) (Don had a big role in creating these):
  - [git tutorial](https://geohackweek.github.io/Introductory/03-git-tutorial/)
  - [Conda installation](https://geohackweek.github.io/preliminary/01-conda-tutorial/)
  - [How to use conda](https://geohackweek.github.io/Introductory/01-conda-tutorial/)
