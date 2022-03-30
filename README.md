# IDS721 Project 3 Structural Streaming of Data on Databricks
## Structural Streaming of Data  
The goal of this project is to realize the structual streaming of data using Pyspark. Since we are streaming data from one source to another, the first step to do is to set up the schema and the structure of the data. The simulated dataset shows the status of different IOT appliances.  
The focus of this demo is to showcase the streaming of data, so I will not build a lambda function on AWS to scrape JSON payloads from APIs and get new data from time to time. Instead, I uploaded 20 JSON files all at once to databricks and then I will use PySpark to read in one JSON file at a time to emulate the streaming process of incoming new data.  
The streaming dataframe is created. The next step is to set a destination for the data to get streamed into. I can write a query to view the process of streaming data in the real time.  
![image](https://user-images.githubusercontent.com/90075179/160764069-4309e95b-c8af-4825-9961-1c9bfe290a73.png)
![image](https://user-images.githubusercontent.com/90075179/160764129-18c8e10a-3818-43dc-a6a7-2a4269fb385c.png)
