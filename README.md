# 2017 BiG-CZ / ODM2 Hands-On Workshop,
November 15-16, 2017 at UC Riverside, CA.

[2017-BiGCZ-WorkshopAgenda](https://docs.google.com/document/d/1yZImXnbeH0yPvxq0iLbl8Oju_z3Sr39nTjQchOQ65jY/edit#) Google Doc.

## Workshop Topics
We provide information, links and other helpful content on separate pages for each of the twelve workshop topics:

1. [Introduction to BiG-CZ & ODM2](https://github.com/BiG-CZ/bigcz_wshp2017/blob/master/1-IntroBiGCZ-ODM2.md)
2. [Demo of ODM2 on Jupyter Hub](https://github.com/BiG-CZ/bigcz_wshp2017/blob/master/2-DemoODM2JupyterHub.md)
3. [More on ODM2 Controlled Vocabularies](https://github.com/BiG-CZ/bigcz_wshp2017/blob/master/3-ODM2ControlledVocabularies.md)
4. [Installing ODM2 from Conda](https://github.com/BiG-CZ/bigcz_wshp2017/blob/master/4-IntallingODM2Conda.md)
5. [ODM2 Datasets, YODA file & Spreadsheet Ingest](https://github.com/BiG-CZ/bigcz_wshp2017/blob/master/5-ODM2DatasetsYODAspreadsheets.md)
6. [Demo of ODMToolsPython Desktop Application](https://github.com/BiG-CZ/bigcz_wshp2017/blob/master/6-DemoODMToolsDesktopApp.md)
7. [Tour of ODM2 Web Applications](https://github.com/BiG-CZ/bigcz_wshp2017/blob/master/7-ODM2WebApps.md)
8. [Tour of BiG-CZ Data Portal](https://github.com/BiG-CZ/bigcz_wshp2017/blob/master/8-BiGCZDataPortal.md)
9. [Using ODM2 with Python & R to Integrate Data](https://github.com/BiG-CZ/bigcz_wshp2017/blob/master/9-ODM2Python&R.md)
10. [Using the ODM2 Admin Web Application](https://github.com/BiG-CZ/bigcz_wshp2017/blob/master/10-ODM2Admin.md)
11. [ODM2PythonAPI](https://github.com/BiG-CZ/bigcz_wshp2017/blob/master/11-ODM2PythonAPI.md)
12. [ODM2RESTfulWebServices & WOFpy](https://github.com/BiG-CZ/bigcz_wshp2017/blob/master/12-ODM2WebServicesAPIs.md)


## Hands-On Content

For this workshop, participants will only need a web-browser and a GitHub account.

Hands-on activities in Python and R will be provided a Jupyter notebooks dynamically running code in a customized, personal environment on JypyterHub. All required notebook files, data files, other code, etc, will be hosted on a second repository:
* https://github.com/BiG-CZ/wshp2017_tutorial_content
* Note for BiG CZ Team: See the issues created on that repo for info on where we're at vis a vis JupyterHub and tutorial contents, problems we're addressing, etc

All other hands-on activities will use web applications.


## Additional Workshop Resources

### JupyterHub test setup

- http://jupyterhub.bigcz.org
- More details, for now, at https://github.com/BiG-CZ/wshp2017_tutorial_content/issues/3
- [JupyterHub tutorial from Geohackweek 2017](https://geohackweek.github.io/Introductory/05-Jupyter-tutorial/)
- https://jupyterhub.readthedocs.io


### ODM2 Jupyter Notebooks

From May 2017 presentation/demo. Hosted on HydroShare, uploaded here as a temporary convenience
- [ODM2 IPython Notebook Examples](https://www.hydroshare.org/resource/ff79d7926f6040c9acd004636b4e4d38/)
  1. [ODM2_Example1.ipynb:](http://nbviewer.jupyter.org/urls/www.hydroshare.org/django_irods/download/ff79d7926f6040c9acd004636b4e4d38/data/contents/ODM2_Example1.ipynb) Create a blank ODM2 database and load controlled vocabulary terms from http://vocabulary.odm2.org in preparation for data loading.
  2. [ODM2_Example2.ipynb:](http://nbviewer.jupyter.org/urls/www.hydroshare.org/django_irods/download/ff79d7926f6040c9acd004636b4e4d38/data/contents/ODM2_Example2.ipynb) Parse water quality sample data from an ODM2 Excel Template file using the ODM2 Python API and write data to an ODM2 database instance and a YAML Observations Data Archive (YODA) file.
  3. [ODM2_Example3.ipynb:](http://nbviewer.jupyter.org/urls/www.hydroshare.org/django_irods/download/ff79d7926f6040c9acd004636b4e4d38/data/contents/ODM2_Example3.ipynb) Read water quality sample data from an ODM2 database instance using the ODM2 Python API for manipulation or visualization of the data.
- [ODM2: An Information Model and Software Ecosystem for Spatially-Discrete Earth Observations](https://www.hydroshare.org/resource/95458e53fe7e474f85642d6a711729b6/) (Powerpoint)

### R

- [Ben Crary's](https://github.com/benjamincrary) Jupyter Notebook in R, that uses HISCentral & WOFpy, via the WaterML R package: [EnviroDIY_Rnotebook.ipynb](https://github.com/BiG-CZ/BiG-CZ-Toolbox/blob/master/ipynotebooks/EnviroDIY_Rnotebook.ipynb)
- [Dylan Beaudette's (et al)](https://github.com/dylanbeaudette) "NCSS-Tech" [R packages for soil data](http://ncss-tech.github.io/AQP/), including Algorithms for Quantitative Pedology (`AQP`) and `soilDB`
- Look into using [Feather](https://github.com/wesm/feather) as common data-frame binary storage format for two-way exchange/interoperability between R and Python-Pandas (see also this [2016 article about feathers](http://blog.cloudera.com/blog/2016/03/feather-a-fast-on-disk-format-for-data-frames-for-r-and-python-powered-by-apache-arrow/)).

### Introductions to git and conda

- Nice and tested resources from the [UW GeoHackweek](https://geohackweek.github.io) (Don had a big role in creating these):
  - [git tutorial](https://geohackweek.github.io/Introductory/03-git-tutorial/)
  - [Conda installation](https://geohackweek.github.io/preliminary/01-conda-tutorial/)
  - [How to use conda](https://geohackweek.github.io/Introductory/01-conda-tutorial/)
