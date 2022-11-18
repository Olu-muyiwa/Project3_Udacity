# (Fordgo bike Data Exploration)
## by (Babafemi Emmanuel 'Muyiwa)


## Dataset

- This datasets reveals the results of Capital Bikeshare customer use acquired for the Capital Bikeshare service.
- This data set includes information about  bike-sharing system covering Arlington County, VA, the City of Alexandria, VA, Montgomery County, MD, and Fairfax County, VA,  etc, all within the District of Columbia in Washington. The dataset used for this project was the one collected for the month of October in the year 2021. This dataset is open source, at it is available for download at https://s3.amazonaws.com/capitalbikeshare-data/index.html.

- This project amongst other deliverables aims to answer the following questions:
    - When are most trips taken in terms of time of day or day of the week?
    - What type of bike do riders prefer?
    - When are most trips taken in terms of time of day or day of the week?<br>
    - How long does the average trip take?<br>
    - Does the above depend on if a user_type (member or casual)?<br>
    

- This project made use of python program and the visualization libraries like SEaborn, matplotlib and Numpy. The first part of the project  consists of the exploratory data analysis. the dataset variables were explored in order to understand the data's structure, patterns and relationships. This structured analysis were further sub-divided into univariate, bivariate and multivariate analysis.

-The second part of this project contains the explanatory analysis through a slide-deck from jupyter notebook, where insights from the first part of the project were communicated through polished, explanatory visualizations to communicate my results.

## Summary of Findings
--This section shows plot that reveals relationships between 2 variables.
- The findings here are divided into three, they are from (1) Univarite, (2) Bivariate and (3) Multivariate exploratory analysis.
Findings from (1):<br>
- 61.1% of the riders are members(i.e, they are officially registered with Capital Bikeshare), while 38.9% are casuals. 
- Riders prefer weekends to ride, that is Fridays, Saturdays and Sundays, the most preferred being Sauturdays.(This part will be in the explanatory section)<br>.
- The most prefered start time for riders is around 5pm and 6pm. This might be that most riders take a ride after work.<br>
- The duration of the ride in minutes has its peak at 8 minutes this was reavealed after applying the logarithm scale to the x axis.(This part will be in the explanatory section)<br>.
-There are three types of bike available, classic, docked and electric bikes.The most prefered type of bike is the classic bike having about 78.5% of the rides.

Findings from (2) <br>
-Most casual riders prefers Saturdays and Sundays, while members prefer Saturday, Friday and Thursdays.(This part will be in the explanatory section)<br>
- Both members and casuals like to ride the classic bike, followed by electric bike. Members hardly use the docked type of bike.
-The map reveals that between the hour of 5pm and 6pm is the favorite time for riding bikes, and those rides do not extend beyond 100 minutes.(This part will be in the explanatory section)<br>
-Riders who use docked type of bike usually spend between 20-60 minutes.

Findings from (3) <br>
-This section shows plot that reveals relationships between 3 variables.
- On all days of the week, the electric bike does not travel longer than other bikes in terms of duration of ride.<br>
- On wednesdays the duration of docked type of bike reduced.<br>
-The scatter plot of duration above 800 minutes shoows that;
-There are more casual riders than members in this category.
-There is intersection of casual and member riders around 5 and 6 pm(17&18 hours).(This part will be in the explanatory section).



## Key Insights for Presentation


- The following key insights will form part of my explanatory presentation.
    - The percentage of user type (members and casuals). <br>
    - The relationship between the type of bike and duration of ride.<br>
    - The hour of the day and day of the week that the riders prefer.
    - The relationship between duration of ride, hour of the day and user type.


