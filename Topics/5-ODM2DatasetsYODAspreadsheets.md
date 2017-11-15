# ODM2 Datasets, YODA file & Spreadsheet Ingest
Presenting: Anthony, Steve


### ODM2 Datasets
[ODM2 Datasets](https://github.com/ODM2/ODM2/blob/master/doc/ODM2Docs/core_datasets.md) are the primary unit for data from ODM2 to be shared, published and archived, as they:
* Contain one or more Results, as many as specified by the user
* Include a Title and Abstract (optional)
* Can be linked to Authors and Citations
* Have a Universally Unique Identifier (UUID) for unambiguous provenance.

ODM2 Datasets can contain all of the fields shown in the [ODM2 Overview Entity Relationship Diagram](http://ODM2.github.io/ODM2/schemas/ODM2_Current/diagrams/ODM2OverviewSimplified.html)

### YAML Observation Data Archive (YODA) Profiles

The [YAML Observation Data Archive & Exchange (YODA) File Format](https://github.com/ODM2/YODA-File/tree/master/README.md) was developed as a specification for for exchanging a specific type of ODM2 Dataset -- one in which **Results are grouped into a single two-dimensional data array** similar to how scientists most commonly view their data (e.g. in tables or DataFrames).

[YODA Profiles](https://github.com/ODM2/YODA-File/blob/master/doc/YODA_profiles.md#yoda-profiles) have been developed for common dataset types to define expectations for the data array block and to facilitate data/metadata input forms/templates for the end-user. We have developed three YODA Profiles to date:
1. Time Series
2. Specimen Time Series
3. Specimens (under development)

These YODA Profiles have been implemented in both YAML and Microsoft Excel Spreadsheet representations.

We envision numerous future [YODA Profiles](https://github.com/ODM2/YODA-File/blob/master/doc/YODA_profiles.md).

### YODA-Tools Desktop App for Spreadsheet Ingest

The [YODA Tools](https://github.com/ODM2/YODA-Tools) library, which is built upon the [ODM2PythonAPI](https://github.com/ODM2/ODM2PythonAPI), was developed to ingest datasets from our [YODA Excel Templates](https://github.com/ODM2/YODA-File/tree/master/excel_templates) and load these datasets into ODM2. [YODA Tools](https://github.com/ODM2/YODA-Tools) can also create YODA Files from these Excel Templates or from an operational instance of an ODM2 database, or read YODA Files directly into an ODM2 database.

YODA Tools has a simple desktop application, in addition to providing all functions in Python.


#### [Back to Workshop main page](https://github.com/BiG-CZ/bigcz_wshp2017/blob/master/README.md)
