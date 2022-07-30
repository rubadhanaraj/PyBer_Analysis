# PyBer_Analysis
## Overview of the analysis
The PyBer analysis is an exploratory analysis based on ride sharing data from PyBer. To aid this process, several types of visualisations were created with Python scripts using Pandas library, Jupyter notebook and Matplotlib to create variety of charts to showcase the relationship between the type of city, the number of drivers and riders, as well as the percentage of total fares, riders and drivers by type of city.
### Purpose of the analysis
The Purpose of the analysis is to find the total weekly fare metrics of each city type using Pandas and Matplotlib. The analysis shows how the data differs by city type and how those differences can be used by decision-makers at PyBer.
### Resources
Software : Python, Jupyter Notebook

## Results 
The PyBer summary dataframe of ride sharing data between Jan 2019 and April 2019, shows that,
![image](https://user-images.githubusercontent.com/108298416/181870227-2e04561e-94cd-494f-bebf-a4ea72e40ed0.png)

* The total rides count in urban city type is higher than the suburban and rural city types.

![image](https://user-images.githubusercontent.com/108298416/181870967-ce2fa1bd-74d8-4f30-85ce-327d955e6392.png)

* Urban cities have more drivers than suburban and rural cities. 

![image](https://user-images.githubusercontent.com/108298416/181870986-e0c4bd9d-4e53-4059-b0b1-cddf731f2c1d.png)

* The average fare per ride and average fare per driver is higher in Rural cities
![image](https://user-images.githubusercontent.com/108298416/181870678-8fcf200d-e448-495b-bee0-fd5927cfaaf7.png)

The multiple line chart was created by using different functions in pandas and a dataframe was created. Pivot funaction was used to create a dataframe to get the total fares for each type of city by the date. Using the loc function the another dataframe was created on the given dates from the pivot table. The "date" index is changed to datetime datatype which was necessary to use resample method. Uding resample method in weekly bins, a dataframe was created to find the sum of fares for each week in each city type

![image](https://user-images.githubusercontent.com/108298416/181871518-41da8ca6-aeba-478d-8104-d76f64c1bfe6.png)






