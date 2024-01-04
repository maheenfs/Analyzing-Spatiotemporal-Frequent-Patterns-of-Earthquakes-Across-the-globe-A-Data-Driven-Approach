# Analyzing-Spatiotemporal-Frequent-Patterns-of-Earthquakes-Across-the-globe-A-Data-Driven-Approach
The objective of the project could be to explore patterns and relationships in the earthquake data, detect clusters or anomalies, and visualize the findings to facilitate better understanding and decision-making related to earthquakes

For the purpose of this project, we used the data offered by usgs.gov for our project to get information on earthquakes occurred between 1568 to 2018. The map below shows the study area that makes up the Central and Eastern United States Earthquakes Dataset. 

This database has been downloaded and transformed from https://www.sciencebase.gov/catalog/item/63c844acd34e06fef14f3408 as eqcat_CEUS1568-2018.txt(.csv) into a "EarthQuake.csv" file for ease of use in our project

Dask: 
Mainly used for handling big data processing and computations that exceed the memory capacity of a single machine.

Pandas:  
Pandas are a fast , powerful, flexible, and easy to use open - source data analysis and manipulation tool.
Offers  data structures and operations for manipulating numerical tables and time series.

NumPy: 
Numerical Python, is one of the most valuable libraries in Python, with numerous built-in functions. It can be used to perform various mathematical operations on arrays.


Tensorflow: 
A flexible, open-source library for deep learning and numerical computation. This machine learning framework makes building models more straightforward, faster, and more reproducible. 

Matplotlib:  
It is a cross-platform data visualization and graphical plotting library for Python and its numerical extension NumPy.

Sci-kit learn: 
A popular python machine learning library for getting started with machine learning. 
Provides efficient tools for machine learning and statistical modeling.


Machine Learning with PySpark:

We first initialize a SparkSession and convert the Pandas Data Frame to Pyspark Data frame. And then create a VectorAssembler to assemble the feature columns into a single features column. We then apply PCA (Principal Component Analysis) to the features in the PySpark Data Frame, and then determines the optimal number of clusters (k) using K-means clustering and the Silhouette score. The value of k that yields the highest Silhouette score indicates the optimal number of clusters. 


