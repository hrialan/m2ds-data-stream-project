# Data streams processing project

## Real-time streaming application with Kafka 

<img src="Google_Facebook_Amazon.PNG" width="400"></img>

Authors : __Cyril Nérin - Hugo Rialan - Alexandre Perbet__

--- 
### Project Description 
The objective of the project is to predict markets stocks using online regression tools
The stock exchange rates used are as follows : Google, Facebook, Amazon, Total, Gazprom, Alibaba, BNP Paribas, Ferrari

We first developed a batch regression solution. Then, we developed an online solution using river and Kafka.

--- 
### Project Architecture

The project was carried out on Jupyter notebooks to improve the visibility of the results obtained. 

3 notebooks are available : 

- The **first** one contains the data ingestion and an implementation of the ARIMA algorithm for the batch part.
  <div align="center">
  <img src="Archi_KAFKA.PNG" width="400"></img>
  </div>
  
- The **second** one contains the online learning prediction algorithm implemented with River.
  <div align="center">
  <img src="Archi_KAFKA_2.PNG" width="400"></img>
  </div>
- The **third** one allows to display and plot the obtained results.
  <div align="center">
  <img src="Archi_KAFKA_3.PNG" width="400"></img>
  </div>
  
  
 --- 
### Requirements

It is assumed that Zookeeper is running default on localhost:2181 and Kafka on localhost:9092 before running the notebooks.
