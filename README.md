# starter_folder

This repo....

It is organised as follows...

In this report, I introduce the Toronto public safety background and the major concerns about public safety hazard. The dataset I used collects fire incidents data in Toronto. Then, I introduce the observations, variables of the dataset as well as how the data is collected. The pros and cons are also mentioned in the report. I give some possible improvement on future data collection. Then, I analyze the relationship between estimated dollar loss and number of exposure fires, civilian casualties, building status. Finally, I give my data analyzation result based on the previse work.

clean the data
data0= na.omit(data)
data1<-data0%>%
  select(Estimated_Dollar_Loss,Exposures,Civilian_Casualties,Area_of_Origin,Building_Status,Possible_Cause )