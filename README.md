# Template CIT002
## Template shortcuts
* UI5 webapp
* ui5-tooling as main dependency
* MTA
* sap/approuter inside

## Template description
This repository is a demo repository to use SAP ui5-tooling module, a ui5.yaml file to define the libraries and middlewares for local development and a mta.yaml to deploy into an container on a Cloud Foundry environment.  
The UI5.yaml is used to build all necessary dependencies, but the zip file will be generated by MTA / mbt build. This file will be used to deploy it into the container.  

This template is containg his own sap/approuter module and therefore, the webapp will not be deployed to a HTML5 service on CF - it remains in the webapp folder of the approuter.  
The approuter is acting as kind of wrapper around the html5 webapp.  

## Requirements
* Install the devDependencies defined inside 'package.json' (by using npm install) on your device
* You do not need to add any services first, but you can add e.g. destinations after the first deployment on the binded destination-service-instance.

## Contact and Credits
Please check licences for each npm module on your own, before using it on your production.  
Come back to us, if you need guidance or more information about it.  
CIT Focus EG  
www.cit-focus.com  