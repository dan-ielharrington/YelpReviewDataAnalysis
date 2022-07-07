# Analyzing Yelp Business Intelligence Data
***

Daniel Harrington   
***

### Project Description
***
This project is an analysis of publically-available data from Yelp’s Businesses and Reviews dataset. The analysis was performed utilizing a Spark Cluster through Amazon Web Service’s EMR and connected to a Jupyter Notebook, which was created to run queries against the dataset. All necessary libraries are installed and imported at the beginning of the Analysis.ipynb file.

In order to successfully replicate the results of this project, please ensure that you create a EMR Spark Cluster using Relase: *emr-5.31.0* and select Hadoop 2.10.1, Hive 2.3.0, Hue 4.10.0, Spark 2.4.8 and Livy 0.7.1 from the Software Configuration options. (Refer to the images below for clarity). 
The cluster used in this project consisted of three m5.xlarge nodes. Once the EMR cluster is up and running, create a Jupyter Notebook file from the "Notebooks" option to the lefthand side of the AWS EMR interface. This will generate a Jupyter Notebook running a Pyspark kernel. 

_Note: there is a known issue when attempting to import the Seaborn library in this particular project. Therefore, I have opted to conduct all visualization using functionalities imported from the matplotlib library instead._

***
### Datasets
The datasets used for this project can be found here: https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset

Each dataset was uploaded to an AWS S3 bucket and then converted into a Spark dataframe throughout the development of the project. Please refer to the .ipynb file for appropriate syntax.  


# Configuration Documention
***

### Spark Cluster Configuration: 


![cluster_configuration%20copy.png](attachment:cluster_configuration%20copy.png)

***
### Jupyter Notebook Configuration: 

![notebook_configuration%20copy.png](attachment:notebook_configuration%20copy.png)
