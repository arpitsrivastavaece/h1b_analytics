# h1b_analytics
The project aims to do analysis on H1B data from 2016 and provide insights.<br/> 
Also, it tries to provide a prediction of H1B approval based on the applicant's credentials.<br/>
The original dataset can be found on <a href="https://www.kaggle.com/jonamjar/h1b-data-set-2017/data">kaggle</a>.<br/>


### Architecutre
![Architecutre](/BigDataProject_Architecture.png) 

### Approach
1. It uses PySpark to process the data over HDFS
2. Map reduce code is run to generate a list of X and Y, which is then plotted using matplotlib
3. PySpark mllib, which is a RDD based Machine Learning Library, is used to do data modeling

### Usage
1. Jupyter notebook along with PySpark will be required to run this project.
2. Make sure the file path is correct (we used hdfs, however any file system can be used).
