# Tableau_Homework_Citi-Bike-Analytics
____________________________________________________

## A Tableau Story Board 
_____________________________________________________
![bicycles-4245347_1280](https://user-images.githubusercontent.com/82990618/134762536-2beab69e-32ee-48ae-8f48-b59af160df89.jpg)


### Contributor: 

**Valense Acquah-Louis**

**For this homework, we take a look at New york City Bike data and created a Story Board on Tableau to help**
* Take a look at how effective the program has been
* The effect of COVID-19 on the program
* Other analysis like the average age of riders, gender, subscribers etc.

**Description:**

There Story Board is made up of four Dashboards with 2-6 visualizations. These visualiztions are madeup of maps, horizontal, bar and line charts. 

For this Tableau Story Board we are going to explore mainly the effect of COVID-19 on the Citi Bike program in New York. To do this data from start of the program 2013 is analyzed  in addition for data from 2018 which serves as pre COVID-19 data and data from 2020 as during COVID-19 data. 

**Cleaning and preparing data:**
* Source Data as CSV were obtained from
    * https://ride.citibikenyc.com/system-data or
    * https://s3.amazonaws.com/tripdata/index.html
* Some select months to represent the seasons of the year were selected and the CSV were converted to dataframes. 
* These dataframes were then concated into one for the analysis
* Some columns were converted into strings for the sole purpose of the analysis
* And an additional column 'age' was created  and some seleTransform (Fill in the Gaps)
* After cleaning the dataframes were converted back to CSV

### The Story Board
**Mapbox visuals of Start and End Stations**
![Mapbox](https://user-images.githubusercontent.com/82990618/134763712-67c485c9-3e7b-4b59-931d-932bb2c67e47.PNG)
* This visualiztion shows the analysis the start and end stations between the years 2013, 2018 and 2020 
* The Map shows the frequently used start and end station for each year was the same but from start of the program 2013 to pre COVID-19 2018 amd during COVID-19 the frquently used stations were different. 
* The stations are as follows:	
           |Start Station	       |End Station          |
    |----------------------------|---------------------|
    |2013  |E 17 St & Broadway	 |E 17 St & Broadway   |
    |2018  |Pershing Square North|Pershing Square North| 	
    |2020  |1 Ave & E 68 St	     |  1 Ave & E 68 St    |
**Bar Charts of Usertype**
![Usertype](https://user-images.githubusercontent.com/82990618/134784580-496282db-0020-45f2-8cf8-a18e52e9870e.PNG)
* From the onset of the program, the number os subscribers to the program has always been higher than that of the customers
* The data shows an increase in both numbers from 2013 to 2018 but interestingly the number of customers doubles from 2018 to 2020 (i.e. pre and during COVID-19)
* As expected the number of Subscribers decreases
* In all the data shows the program was successful and this will help with carbon emmissions

**Bar Chart by Gender through the years**
![Gender](https://user-images.githubusercontent.com/82990618/134784811-0197c90a-3009-4eb3-94c9-2859883eff3e.PNG)
* The goal to get more female riders to patronize the bike riding program was a success.
* In general there was an increase in the number of riders who male and female but a decrease in those with unknown gender
* The numer of female riders increased in 2020 during COVID-19 where as there was a slight decrease in make riders.
* The number of bikers with unknown gender decreased form start of the program in 2013, there is a slight uptake in the number of these riders in 2020.

**Line Chart of average trip by age of riders**
![average trip](https://user-images.githubusercontent.com/82990618/134785148-d255acf0-c18c-456f-9941-a7f20480b3ee.PNG)
* This line chart shows the average trip taken by riders by their age
* THe riders with unknown gender had the highest average trip recorded for both 2018 and 2020. The average age of these riders were in the 20s
* Next is the number of females with ages 19 and 49 having high average trips in 2018 to those who were 17 coming in with the highest average trip in 2020
* The age for males were about the same like in the case of females in 2018 and 2020 but the males hade a lower trip average than females and those with unknown gender. 



**Tableau Profile:**
https://public.tableau.com/app/profile/valense.acquah.louis/viz/CitiBikeAnalysis_16324417359490/CitiBikeAnalysisfromstartofprogramthroughtheyears
