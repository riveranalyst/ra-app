# River Analyst App repository
River Analyst is a database application framework built with the [Django](https://www.djangoproject.com/) web application framework (Python) to leverage fast river ecosystem analyses. 

This repository build on the river analyst software (https://github.com/riveranalyst/software) to deploy a web app with Railway. Thus, this repository contains the same front and backend coded, but it has additional files necessary to deploy River Analyst online, such as "Procfile" and "get-pip.py". 

Any pushed changes to this repository will trigger a re-build of the web app, and thus also re-deployment. The opposite is however not true: any additions to the online database will not update this repository. This means that changes can only be pushed to this repository when ensuring that the last database version has been downloaded (go to Query tab in the web app).
