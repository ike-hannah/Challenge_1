# Kickstarter Analysis
The purpose of this project is to compare the outcomes of Kickstarter campaigns based on their respective goals and launch dates. Using a data set of many different types of campaigns, I compared the results of campaigns in the theatre space for a client who has already launched a successful campaign.
## Analysis and Challenges
### Theater Data Based on Launch Date
Begining with the raw data from about 4200 Kickstarter campaigns, I created a few extra categories to make looking at the data easier. From the raw unix date codes I created a time conversion colomn and subsequently pulled the years into their own seprate coloumn. From there I created a pivot table and accompanying pivot chart based on the date that the campaign was launched and whether it was successful, failed, or was canceled. The table can also be filtered by parent category. The chart reflects data from only the "Theater" category. ![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/65744738/146284078-efdce9e9-0161-4e20-a8d8-ff7d67ef2ba4.png)
### Theatre Data Based on Goal
I also created a separate sheet collecting the outcomes of campaigns based on their fujding goal. The goals were sectioned out into 5000 dollar chunks starting from less than 1000 and going to greater than 50000. The rest of the sheet was populated from the raw Kickstarter data and also inclues the sum of all projects based on funding strata, as well as percentages for successful, failed, and canceled projects. This sheet was turned into a line chart using ma pivot table. 
![Outcomes_vs_Goals](https://user-images.githubusercontent.com/65744738/146284535-3ea3fdb4-38d1-4994-9cc9-a966450aeb72.png)
## Results
From the data representing outcomes based on launch date in the theater category we can see that May is the best month to launch a campaign with by far the most amount of successful campaigns launched while December seems to be the worst with almost as many failed projects as successful ones.

From the data representing outcomes based on goals we can see a good amount of successful campaigns in the under 1000 to less than or equal to 200000 dollar range. From 20000 to about 32000 we see a sharp decline in the number of successful campaigns, however there is a reversal of the trend from 35000 to 45000. Beyond the 50000 dollar range it is very likely that a campaign will fail. 

There are a few limitations with this data one being that having more data is always helpful. There are also a few outliers in the data set that could be skewing some aspects of the data overall.

There is extra data in the raw kickstarter sheet that would be intersting to analyse. There are two coloumns labeled "staff pick" and "spotlight", these two categories must have some impact on how a project fairs in that the more people see a project the more potential backers a campaign is shown too. I would also be interested in looking at how the overall backer count and average donation affects the outcome of a campain
