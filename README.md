# What is Layer?
Layer is a [Declarative MLOps Platform](https://layer.co/) that empowers Data Science teams to implement end-to-end machine learning with minimal effort. Layer is a managed solution and can be used without the hassle involved in configuring and setting up servers. 


# Getting started
Clone this repo to start a new Layer project. 

Install Layer:
```
pip install layer-sdk
```

Clone this empty Layer Project:
```
layer clone https://github.com/layerml/empty
```

This repo contains a Layer project that you can quickly use to boostrap your machine learning projects.

Note: Use either Python or SQL featuresets template. Layer does not support multiple language featuresets at the moment.

The empty Layer Project has the following files:

```
|____.layer
| |____project.yaml                      # Main project configuration file
|____data
| |____dataset
| | |____dataset.yaml                    # Definition of the source data
| |____features
| | |____sql_featureset                  # Template for SQL featureset
| | | |____sql_featureset_feature1.sql   # SQL file for your feature
| | | |____sql_featureset_feature2.sql   # SQL file for your feature
| | | |____dataset.yaml                  # Definition of your sql featureset
| | |____python_featureset               # Template for Python featureset
| | | |____python_featureset_feature1
| | | | |____feature1.py                 # Python file for your feature
| | | | |____requirements.txt            # Environment config file, if required 
| | | |____python_featureset_feature2
| | | | |____feature2.py                 # Python file for your feature
| | | | |____requirements.txt            # Environment config file, if required 
| | | |____dataset.yaml                  # Definition of your Python featureset
|____models
| |____model
| | |____model.py                        # Training directives of your model
| | |____model.yaml                      # Training directives of your model
| | |____requirements.txt                # Environment config file, if required               
```
