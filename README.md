# Udacity's Data Scientist Nanodegree Project 03: Identity Customer Segments

--------------------------------------
1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## 1. Installation <a name="installation"></a>

- This code was created by using Python versions 3.*.
- Following libraries have to be imported:

* pandas
* numpy
* matplotlib
* seaborn
* random
* scikit-learn
* IPython
* operator

- copy repository: git clone https://github.com/oliverkroening/Udacity_DSND_Project03


## 2. Project Motivation <a name="motivation"></a>
For this Udacity project, I applied unsupervised learning techniques to identify segments of the population that form the core customer base for a mail-order sales company in Germany. These segments can then be used to direct marketing campaigns towards audiences that will have the highest expected rate of returns. The data I used has been provided by Bertelsmann Arvato Analytics, and represents a real-life data science task.

## 3. File Descriptions <a name="files"></a>  
Since the data is proprietary, I am not allowed to publish the raw data here.

* Identify_Customer_Segments.ipynb: Jupyter Notebook including the whole process to fulfill the tasks of this project.
* Identify_Customer_Segments.html: the corresponding HTML-file

## 4. Results <a name="results"></a>
To investigate the general and customers datasets, we performed following steps:
- create predictions for the general and the customers data using the KMeans model
- count the observations grouped by the predicted cluster (0 - 9) for each dataset
- calculate the proportion of each predicted cluster within each dataset
- compare the proportions between the general and the customers dataset
- identify clusters in which the customers are overrepresented
- identify clusters in which the customers are underrepresented
- calculate the mean values of the features within the clusters to find characteristics

Following final results have been obtained:
Customers might primarly be elderly people. The group in which customers are more overrepresented also usually live in a conservative or upper class neighborhood, whereas the underrepresented cluster is primarly domiciled in middle or lower middle class neighborhoods (feature REGIOTYP)

## 5. Licensing, Authors, Acknowledgements<a name="licensing"></a>
All data was obtained from Bertelsmann Arvato Analytics as well as Udacity, thus, I must give credit to them. Other referebces are cited in the Jupyter notebook.






