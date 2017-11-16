# Tour of ODM2 Web Applications
Presenting: Jeff

### EnviroDIY Water Quality Data Portal
The [EnviroDIY Water Quality Data Portal](http://data.envirodiy.org/) is a Python/Django-based web application and web service for registering data collection devices and allowing them to stream sensor observations into an online instance of an ODM2 database. It is built on the following ODM2 Software components:
* ODM2 Web Streaming Data Loader :https://github.com/ODM2/ODM2WebSDL
  * Implements simple REST web service for devices to POST data to the service and have it stored in an ODM2 database instance as the backend
  * Implements a front end website for users to register sites/data collection devices, list the observed variables, and create the metadata needed to enable data streaming.
* WOFpy: http://data.envirodiy.org/wofpy/
* Time Series Analyst: http://data.envirodiy.org/tsa/
* R ShinyApp: https://limno.shinyapps.io/envirodiy_crossroads/

### Other ODM2-based Web Apps
* HydroShare time series in ODM2
* Specimen Data Viewer: https://github.com/ODM2/SpecimenDataViewer
* ODM2Admin: https://github.com/ODM2/ODM2-Admin
  * More tomorrow with topic 10
* ODM2 servers, databases and service resources available for demoing and testing
  * https://github.com/BiG-CZ/bigcz_wshp2017/issues/1


#### [Back to Workshop main page](https://github.com/BiG-CZ/bigcz_wshp2017/blob/master/README.md)
