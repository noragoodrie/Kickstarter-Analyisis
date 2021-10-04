# Kickstarter-Analyisis
Theater-Based Kickstarter Campaign Analysis

**OVERVIEW OF THE PROJECT AND PURPOSE**

This week’s project was largely focused on how to perform an analysis on theater based crowdfunding campaigns where we took the Kickstarter data and broke it down into many different parts to unfold what Louise was looking for. The spread sheet at hand was filled with campaigns from 2010 through 2017 where we are able to see the successful, failed, cancelled and live campaigns of a large range of categories. Due to the fact Louise was focusing on theater campaigns we were able to grab all the data that was needed. The main tool used was Microsoft Excel where pivot tables, data charts, a handful of formulas were used to break down the data set.


**ANALYSIS AND CHALLENGES**

The best way to start your analysis is looking through the data and understanding what you are working with. You should always check and see how many. Rows and columns you are working with and what the names of the columns are, that way you get the gist of what you are working with.  

 

As you can see above the data set first started with columns titled, Names, Blurb, Goal, Pledged, Outcomes, Country, Currency, Deadline, Launched At, Staff Pick, Backers Court, Spotlight and Category/Subcategory.
I then later added 7 additional data sets that gave the ability to have a deeper understand of the data at hand.

Percentage Funded (=ROUND(E2/D2*100,0)
Average Donation (=IFERROR(ROUND(E2/L2,2),0))
Parent Category (Found by splitting apart Row N)
Subcategory (Found by splitting apart Row N)
Date Created Conversion (=(((J2/60)/60)/24)+DATE(1970,1,1))
Data Ended Conversion (=(((I2/60)/60)/24)+DATE(1970,1,1))
Years (=YEAR(S2)

**ANALYSIS OF PARENT CATEGORIES**

![Screen Shot 2021-10-03 at 10 31 53 PM](https://user-images.githubusercontent.com/91299616/135798947-41296c48-754b-482d-8257-f29fc9afd77c.png)


 

After all the columns and new data sets were formatted, it was time to use the data and visualize it into Pivot Tables and Charts. 

Let’s look at the pivot table first. This Pivot Table is analyzing the Parent Category Data in the US for Canceled, Failed, Live and Successful Campaigns. We can see that “Theater” has the most successful campaigns in the US!

Now looking at the bar graph it verifies that “Theater” has the highest success rate in campaigns.























**ANALYSIS OF SUBCATEGORY**

![Screen Shot 2021-10-03 at 10 33 23 PM](https://user-images.githubusercontent.com/91299616/135799075-30c220f8-013c-4b29-a0df-88a2590fbac9.png)


 
(View Table Above)

The Pivot table has column and values of outcomes, rows of subcategories, filters of country and parent category. In this chart we can see that “Plays” which is a subcategory of Theater, has the highest success rate in campaigns compared to 40 other subcategories. 

















**ANALYSIS BASED ON OUTCOMES BASED ON LAUNCH DATE**

![Screen Shot 2021-10-03 at 10 35 17 PM](https://user-images.githubusercontent.com/91299616/135799206-5c2aee43-a7ab-499a-82e5-097c1c5b8d8d.png)



 


This Pivot Table was created to see the Theater Outcomes Based on Launch Date data. As you can see the row labels show you the Month from Jan – Dec of “Successful”, “Failed” and “Canceled” campaigns. With this data we can see that for successful campaigns May had the highest number in total. From this data set we can tell that the best time to launch a new campaign for it to be successful is the first half of the year.






















**ANALYSIS OF OUTCOMES BASED ON GOALS**

![Screen Shot 2021-10-03 at 10 35 54 PM](https://user-images.githubusercontent.com/91299616/135799268-30ec7b9d-5861-4bd3-9841-2190067e2b7c.png)

This data set was created to see how many successful, failed, and canceled projects were created due to the goals column. The goals column ranges from “less the 1000”, “1000 to 4999”, “5000 to 9999”, up to the final data set of “Greater than 50,000”. The line graph was created to show the relationship between the amount the goal has and the chances the campaign has in being successful, failed or cancelled. 


**CHALLENGES**

Throughout this analysis one of the main functions used are pivot tables. Pivot tables are very resourceful, and it is a great way to see large data sheets condensed into what you are truly looking for. With that being said, don’t let these pivot tables fool you, they can be hard to work with. When you are new to Pivot tables it is easy to get confused on which data goes into the values, columns, rows, and filter categories. Sometimes when you put things in the wrong spots your data will look correct when it really isn't, so you will need to go over your work and get familiar with what your purpose with conducting a pivot table really is

**RESULTS**

 Q: What are two conclusions you can draw about the Outcomes based on Launch Date?

1.	May has the highest number of successful campaigns in total compared to failed, and cancelled campaigns. 

2.	We can tell that the best time to launch a new campaign for it to be successful would be in the first have of the year.

Q: What can you conclude about the Outcomes based on Goals?

1.	We can conclude that your campaign does NOT have a higher success rate with the more money you put into it. We can see that because it is a crowdfunding Kickstarter you will find more success in a lower budgeted campaign.

Q: What are some limitations of this dataset?

1.	Some limitations of this dataset are that it we have data from 2009 – 2017. That is 8 years between the two and times change every year. You are trying to get investors to invest in a kickstart right after/ during the recession so our success rate may have been higher at the beginning years of this data.

Q: What are some other possible tables and/or graphs that we could create?

1.	We could use another graph to represent all the subcategories besides “plays” to find another subcategory to focus on. (If we needed a backup from theater)

2.	We could have charted another dataset for successful outcomes to see how long the campaign was running for. (As if another timeline) 
