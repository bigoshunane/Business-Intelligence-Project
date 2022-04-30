# New York Citibikes Analytics

The aim of this project is to aggregate the data found in the Citi Bike Trip History Logs of New York City and find unexpected phenomena and 
design number of visualizations for each discovered phenomena.

# Data source
Monthly CSV files of 2020 (01/2020 to 12/2020) were collected from [Citi Bike Data](https://ride.citibikenyc.com/system-data) webpage. Since the files size exceeeds github limit I could not be able to git push in to the repositroy, but the files can be found in repo as bikes.twbx.


# Visualizations
Few Visualizations with story telling are published on public tableau and found at this [link](https://public.tableau.com/app/profile/workineh.shunane1801/viz/bikes_16511366012330/Story1?publish=yes). Note, I had to cut some visualiaztions from publishing on public tableau due to the limit of rows set by the software and my data rows exceeded the limit i.e. 15 000 000. As a consequence more visualization dashboards are computed and available at [file](https://github.com/bigoshunane/Tableau-Homework-13/blob/main/bikes.twbx) in repository. Moreover, listed in pictures below are list of visulazations together with analysis I have developed.



# Analysis

1. Number of Records

Total number of records were about 19 million. It appeared that ore bikes ride were recorded in the summer than in the winter. 
The possible reason could be that people are not willing to ride outside in winter due to the cold weather. September, 2020 had the
highest number of recordes at 2 488 101. while April,2020 had the lowest one at 682 744. In May, 2020 , the
number of records went up by 117 %, while December,2020 showed the lowest records among others.

![a](https://user-images.githubusercontent.com/84547558/165471845-b7784c81-85b4-4163-91cd-c5dd178e34ac.png)

2. Top/Bottom Ten Stations

Top ten stations for both starting and ending a bike trip are at 1 Ave & 68 St. and West St & Chambers St respectively. 
![b](https://user-images.githubusercontent.com/84547558/165472830-327c12da-ded1-4144-9b76-999966ea9706.png)
![map stations ](https://user-images.githubusercontent.com/84547558/165473649-216bcd75-5ab9-4853-aa38-d8b4fefccac2.png)

3. Peak Hours

Rush hours between 17-to-19-PM appeared to be peak hours during summer time for bike riders. 
![c](https://user-images.githubusercontent.com/84547558/165474141-b634edb1-3e3d-4345-b372-44e793175eee.png)

4. Number of Bikes and Distance

Total number of bikes used in New York City based on this data source is 24 982, and their average distance ridden is 1.275 mile. Bike with ID 36962 has the highest mileage of 3486 on it, and is most likely due for repair or inspection. Moreover, bikes are mostly ridden by the annual subscribers.

![bike stst](https://user-images.githubusercontent.com/84547558/165474466-a472dd51-4190-432a-b7b1-1829da3ff476.png)

5. Trip Distance and Duration by Age and Gender

The highest number of records (34,628) were recorded by people aged 51, although majority of the users are aged between 30-45 years old. In terms of the distance and duration, most young users rode citi bikes for short distance, while the older people rode for longer distance and duration. It is clear that men ride way more citi bikes than women and unknown gender. Usage of three categories peaked during Summer, and then decreased after September.

![D](https://user-images.githubusercontent.com/84547558/165623991-4aaae462-6092-4235-9c0d-097cb06baf8b.png)



© 2021 Trilogy Education Services, LLC, a 2U, Inc. brand. Confidential and Proprietary. All Rights Reserved.
