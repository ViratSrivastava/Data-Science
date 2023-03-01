# Data-Science
Category of Data Science Tools:

Data Science requires various tools for various tasks:

![image](https://user-images.githubusercontent.com/98209563/222228966-186ff91d-b913-4529-b017-278eb2532657.png)

1.  Data Management is the process of persisting and retrieving data
2.  Data Integration and Transformation, often referred to as Extract, Transform, and Load, or “ETL,” is the process of recovering data from remote data management systems. Transforming data and loading it into a local data management system is also part of Data Integration and Transformation.
3.  Data Visualization is part of an initial data exploration process and part of a final deliverable.
4.  Model Building is the process of creating a machine learning or deep learning model using an appropriate algorithm with a lot of data. 
5.  Model deployment makes such a machine learning or deep learning model available to third-party applications.
6.  Model monitoring and assessment ensure continuous performance quality checks on the deployed models. These checks are for accuracy, fairness, and adversarial robustness. 
7.  Data asset management brings the same versioning and collaborative components to data. Data asset management also supports replication, backup, and access right management.
8.  Development environments, commonly known as Integrated Development Environments, or “IDEs”, are tools that help the data scientist to implement, execute, test, and deploy their work.
9.  Execution environments are tools where data preprocessing, model training, and deployment takes place
10. Fully integrated, visual tooling is available that covers all the previous tooling components, either partially or completely.

Data Management
Open Source DBMS Tools Available:  
MySQL & PostgreSQL   
NoSQL type DBMS: Mongo DB, Apache Couch DB, and Apache Cassandra   
File-Based DBMS: Hadoop File Systems, Cept(Cloud Based), Elastic Search(text storage and fast data retrieval).  

Data Integration and Transformation
ELT: Extract Load and Transform. Can also be termed as “data refinery and cleansing.”   
Open Source Tools Available:   
Apache Airflow, Apache Spark SQL, KubeFlow, Apache Nifi, Apache Kafka, Node-RED.   

Data Visualization  
Hue: Visualization created from SQL Libraries.   
Kibana: Data Visualization Web-based application.   
SuperSet: Data Visualization Web-based application.   

Model Deployment   
Deployment of the model to other dev by creating an API.    
Apache PredictionIO: Supports only apache based applications such as for providing model deployment.    
Seldon: Versatile application that can work with various workflows such as apache R, TensorFlow, Scikit-Learn etc    
MLeap, Tensorflow Service, TensorFlow Lite, TensorFlow .JS    

Model Monitoring    
ModelDB: can be implemented Metadatabase. Supports apache pipelines, ML Models and Scikit-Learn.    
Prometheus; Use for ML model monitoring.    
The IBM AI Fairness 360 open-source toolkit does exactly this. It detects and mitigates bias in machine learning models.   
The IBM Adversarial Robustness 360 Toolbox can be used to detect vulnerability to adversarial attacks and help make the model more robust.    
The IBM AI Explainability 360 Toolkit makes the machine learning process more understandable by finding similar examples within a dataset that can be presented to a user for manual comparison.   

Code Assets Management    
Also Known as version management. The Standard for this is Git.   
GitHub can use a code host and manage the version of a model.   
Git: Open sources and can be configured for personalized use.   
Gitlab and BitBucket follow the same.   

Data Asset Management   
Data is versioned and annotated with metadata.    
Open Source Data Asset Management Systems: Apache Atlas, ODPI Egeria, KYLO    

IDEs(Integrated Development Environment)    
Jupyter NoteBook: Support Multiple Language    
Jupyter LAB: Next Gen Jupyter NoteBook    
Apache Zeppline: Doesn’t require Coding    
R Studio: Runs Only R and related R Lib and Python   
Spyder: Similar to R Studio   

Execution Environment    
Apache Spark: Batch(Bulk Data-Processing)   
Apache Flink:(Streamlike continuous data processing)    
Ray: Large Scale Deep Learning Model Training    

Fully Integrated Visual Tools    
Refers to environments which require No to Bare-Minimum Coding for use.     
It can also perform all these tasks in a single application.
Open Source Applications: Knime, Orange.

Libraries For Data Science
1.  Python Libraries 
  a.  Scientific Computing libraries
      Also known as frameworks.
      1.  Pandas: Data Structure and Tools
      2.  Numpy: Arrays and Matrix
2.  Visualization Libraries
Used to visualize the data of relevance
Matplotlib: plots and graphs
Seaborn:  Heat maps, time series, and violin plots.
High-Level ML and DL 
1. Scikit-learn: the library contains tools for statistical modelling, including regression, classification, clustering and others. It is built on NumPy, SciPy, and Matplotlib.
2. Keras: Deep Learning Neural Networks.
DL Libraries
1. TensorFlow: Deep Learning, production and Deployment
Apache Spark: Parallel Processing\
APIs (Application Programming Interface)
Allows communication/transfer of data between different two different software.
Dataset
Structured Collection of Data is called Data Set
Tabular - Consists of Rows and Columns
CSV - Commas Separated Values
Heriracy Dataset: Relational DataSets
Raw Data: Images or Audio
