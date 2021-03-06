# Data Analysis with Python

## Overview of Project

### Purpose
The primary purpose of this exercise is to extract the information stored in election_results.csv, organize the data to determine election's outcome and notable statistics, and export the results to a .txt file. This is achieved using Python, utilizing the csv.reader() and write() functions as well as common coding structures to read, manipulate, and write the data.

## Election-Audit Results
*Total Votes Cast

![image](https://user-images.githubusercontent.com/77989740/139598433-36c24d5e-15ca-40d5-ac4b-38a54b428b76.png)

*County-Specific Vote Breakdown

![image](https://user-images.githubusercontent.com/77989740/139598438-c7b239f4-93c5-4dcc-b028-6efda02891cd.png)

*County with the Largest Number of Votes

![image](https://user-images.githubusercontent.com/77989740/139598442-06d6037b-293c-4d54-9f33-4c10d32a7f8c.png)

*Candidate-Specific Vote Breakdown

![image](https://user-images.githubusercontent.com/77989740/139598448-64b71a41-34fd-4162-a0fc-e062e839491b.png)

*Final Election Results

![image](https://user-images.githubusercontent.com/77989740/139598457-c4166ccd-d552-4fe5-ad17-0d562683fdfe.png)

## Election-Audit Summary

This script is capable of generating voting specifics of any election which includes at least one candidate and county. Any supplied data that lists each row as an individual vote, with candidate selection and county of origin formatted the same as election_results.csv, will function properly without modification. The final data may be more unweildy when taking into account the many possible candidates included on a write-in ballot. 

This script can be modified to accomodate a variety of different elections as well. For example, a local election would have no need to track county data. Removing or commenting out the code below that "prints" and "writes" county data will suffice, as long as the candidates remain in the same format of the .csv file and the reference to "County Votes" is removed.

![image](https://user-images.githubusercontent.com/77989740/139599340-686aea0d-85eb-4e50-a2e9-11639b44f7e3.png)

It can also handle a greater scale, such as a national election, with minimal changes. All that's required is to supply a state's name in place of a county, and replace "County Votes"/"Largest County Turnout" with "State Votes"/"Largest State Turnout" in the following code segments.

![image](https://user-images.githubusercontent.com/77989740/139599392-15699ed5-8bac-4d41-b731-885cad3fa2d1.png)

![image](https://user-images.githubusercontent.com/77989740/139599406-866090c7-eb7e-4273-ad2e-25a12966b335.png)



