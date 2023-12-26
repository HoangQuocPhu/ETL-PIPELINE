# Project Object
The primary objective of this project is to construct a system that processes and analyzes log data obtained from users of a job recruitment website. The main aim is to store, handle, examine the log data, and make decisions regarding the future direction of business growth.
# Achitecture
![abc](https://github.com/HoangQuocPhu/datapipeline/assets/117524012/8ea9813f-d9e8-428f-af71-69288c479369)
# Raw Data 
Schema

 ![image](https://github.com/HoangQuocPhu/datapipeline/assets/117524012/d420e850-62c1-409a-9cb5-8969a52e167b)

 ![image](https://github.com/HoangQuocPhu/datapipeline/assets/117524012/5b308cd1-4b52-466b-b642-eb5fe7e8f949)

# Processing Data
Read and review the data recording user actions in the log data, notice that there are actions with analytical value in the column ["custom_track"] including: clicks, conversion, qualified, unqualified. Processing raw data to obtain valuable clean data:

Filter actions with analytical value in column ["custom_track"] including: clicks, conversion, qualified, unqualified.
Remove null values, replace with 0 to be able to calculate.
Calculate the basic values of data for in-depth analysis.
Use pySpark to write Spark jobs and process data efficiently.
Data after processing is saved to Data Warehouse is MySQL for storage and in-depth analysis.
