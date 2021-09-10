# kickstarter-analysis
  ## Overview
-*This project is looking at how other Theatre and Play Kickstarters did based on their launch date and their goal amount.

  ## Analysis and Challenges
  
   ### Analysis of  Theater Outcomes Based on Launch Date
![Theater_Outcomes_vs_Launch.png](https://github.com/AWTENN/kickstarter-analysis/blob/main/Theater_Outcomes_vs_Launch.png)

- For this Analysis,I created a new column called Years to find the Years that the Kickstarter campaigns were started. I then filtered the Category column in the spreadsheet to only have "Theater"  I used a pivottable to compare months to Outcomes and filtered by the Theater Parent Category. I then used a line chart show how the number of outcomes for the Theater Parent Category happened over time. 
          
   ### Analysis of Outcomes Based on Goals
 ![Plays Outcomes_vs_Goals Final.png](https://github.com/AWTENN/kickstarter-analysis/blob/main/Plays%20Outcomes_vs_Goals%20Final.png)
 
- For this analysis, I created a table of data comparing Goals ranging from less than a 1000 to greater than 50000 in Intervals of 5000. I then used the Countifs function to pull the goals data in the interval that was indicated in the row for each Outcome for the Subcategory "plays". After collecting that data, I added all of the outcomes for each Goal interval to get totals for each Interval. Then, I divided the plays based on each outcome by the total plays for each goal interval. After getting the percentages for each outcome for plays, I created a pivottable and compared the goal interval by the percentage of successful and failed plays. Finally, I created the chart seen here using the pivottable described previously.
          
   ### Challenges and Difficulties Encountered
- I only had one difficulty encountered which was self-inflicted, after creating the Countifs functions for the Goals, I had not specified the criteria for "plays". I fixed that by going back entering in the "plays" criteria for the worksheet. There could many other difficulties with the Countifs function, like not knowing the syntax for greater than and less than between two numbers. 
         
  ## Results
   
- Two conclusions that I can draw from the Theater Outcomes Based on Launch Date chart are that the most successful theater KickStarter campaigns happen in May, and that  it would ---  be a high risk to start a Theater KickStarter Campaign in December because the chance the campaign succeeds is the same as the chance that the campaign fails.
 
- I can conclude from the Outcomes Based on Goals chart that KickStarter Campaigns for plays with a goal of less than 5000 are more likely to be successful than all other campaign goals.

- The limitiations of this dataset could be that there were no descriptors of who was creating the KickStarter. Like say if Christopher Walken wanted it for "Walken on Sunshine" it could not get money because he is a famous actor who should be able to fund the play itself. That also is a limitation with the Spotlight column. What kind of Spotlight does it mean? Did the campaign go viral on twitter, did an actor happen to see the campaign and donated handsomely, what qualifies as spotlight? I feel there could be many more conclusions drawn from Author of a Kickstarter , and how Spotlight was gained on a  Kickstarter.

- A chart that I would very much like to see is a chart of Plays Outcomes based on Goals with a filter of Spotlight. I believe that Spotlight is how many people had seen the campaign, and from a cursory glance it looked like many of the successful KickStarters had a Spotlight of "Yes".

      
      
          
          
      

