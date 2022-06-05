# Bikesharing

## Overview
In this project Tableau is the main pprogram that is used to create visualization using data from citibike data in NYC. We downloaded the *201908-citibike-tripdata*, which would be used to create visuals using Tableau. Before using the *201908-citibike-tripdata* first we needed to convert the tripduration to datetime using Jupyter Notebooks and pandas, after converting the tripduration column to datetime, we exported the updated table(*201908-citibike-tripdata_UPDATE*) to our working folder and use the updated csv to Tableau. In Tableau we would create 5 different worksheets which would contain our visualizations, which are 2 line graphs, and 3 heatmaps. After those were created we then added panels to orginize the worksheets that we created into 2 seperate panels, one for the line graph and the other panel for the heatmaps. And we then saved the project to Tableu Public, link will be added at the bottom.
## Results
### Code Conversion:
![JN1](https://user-images.githubusercontent.com/97326526/172066630-701bc583-fe0d-4413-ba28-46accec499a1.JPG)
First we used JupyterNotebook to get the *201908-citibike-tripdata* and read the data into a dataframe.
![JN2](https://user-images.githubusercontent.com/97326526/172066775-583c4aab-2ee2-46a9-a8e7-88538dcaed27.JPG)
After adding the original csv file into the program we would need to convert a specific column from the trip data, the need column would be the tripduration. We convert the tripduration to a datetime datatype, then checking the datatypes of the column by using **.info()** function. After confirming the datatype has been changed then, exporting the new dataframe into a updated csv file without the index.
