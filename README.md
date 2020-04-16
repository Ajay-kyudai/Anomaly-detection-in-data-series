# Anomaly-detection-in-data-series
Anomaly in data series is detected by comparing the anomalous data series with reference data series with the help of SVD (Singular vector decomposition method)
## Explanation of the project
* While analyzing a big continous time series data at every ne minute time interval for several months, it becomes very difficult to detect any anomaly in the data.
* We can understand it more clearly by an example. Let us consider a case, where we have to anlyze the temperature profile of a wind turbine generator by observing the SCADA data for several months. We as a maintenance enginner know the correct tempearture profile, if the turbine is working perfectly. But if any error occurs at any time , then the temperature profile will change. In other words there will be some anomaly in the temperature profile. But it is impossible to detect this small anomaly by just visualizing the data.
* Another example can be the ECG test in medical science to analyze proper heart functioning. For a healthy heart there is a definite ECG profile. But if any problem exists, some anomaly is observed in the profile. Depending upon the severity of anomaly, the physician can detect the  associated health issues.
* In this project an alorithm ghas been devloped to detect such anomaly in a data series by comparing it with refence data series and calculating the anomaly index.
## Pictorial Explanation of the algorithm
![Explanation of Algorithm](https://github.com/Ajay-kyudai/Anomaly-detection-in-data-series/blob/master/Description%20of%20algorithm.jpg)
## Reults
### Direct visualization of anomaly 
![](Images/comparison%20of%20reference%2C%20experimental%20and%20random%20data.jpeg)
### Visualization by anomaly index
![](Images/Anomaly%20index.jpeg)
## How to run
* clone or dowload the files  and run in your terminal
* don't forget to update the location of data files
## Note
* In order to protect privacy original data for the project has not been uploaded
