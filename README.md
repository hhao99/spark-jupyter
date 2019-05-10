spark jupyter 

# Jupyter notebook practice environment 
this is the repository for the pyspark

# prepare the environment
we need the following package installed to the system:

## OS and pre-request 
1. Linux or OSX
2. Python 3.7

## pip and venv 
-> python -m venv jupyter-spark
-> activate the jupyter-spark
-> pip install jupyter jupyterlab
-> pip install py4j

## install the data science toolbox
* pip install numpy panda
* pip install bokeh

## install jdk
download the jdk from https://adoptopenjdk.net
JDK8 or JDK11 is ok for the latest spark

## spark environment
download the spark binary from spark.apache.org
extract to local directory and set the spark-home 
-> export SPARK_HOME=path-to-spark
