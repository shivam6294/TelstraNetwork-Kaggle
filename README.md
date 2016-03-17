# TelstraNetwork-Kaggle

* My Attempt at the [Telstra Network Disruptions](https://www.kaggle.com/c/telstra-recruiting-network) Kaggle Competition 

# Desription 
The goal of the problem is to predict Telstra network's fault severity at a time at a particular location based on the log data available. Each row in the main dataset (train.csv, test.csv) represents a location and a time point. They are identified by the "id" column, which is the key "id" used in other data files. 

Fault severity has 3 categories: 0,1,2 (0 meaning no fault, 1 meaning only a few, and 2 meaning many). 

Different types of features are extracted from log files and other sources: event_type.csv, log_feature.csv, resource_type.csv, severity_type.csv. 

Note: “severity_type” is a feature extracted from the log files (in severity_type.csv). Often this is a severity type of a warning message coming from the log. "severity_type" is categorical. It does not have an ordering. “fault_severity” is a measurement of actual reported faults from users of the network and is the target variable (in train.csv).

# Dependencies
* Please make sure that your have all the files from the [website](https://www.kaggle.com/c/telstra-recruiting-network/data) in a folder <b>Telstra_data </b>, located in the folder where your IPython Notebook is located.
* Please make sure that you have [XGBoost](http://xgboost.readthedocs.org/en/latest/#) Installed. (Good luck if you're a windows user!)
