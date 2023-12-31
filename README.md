# PyCitySchools

![education](https://github.com/stoddow313/Pandas-Challenge/assets/134353666/c6943eef-e68c-4dac-813e-a13467731971)


## Overview: 
In this assignment we took a look through Student and School data by combining them into a single dataframe. By doing this we were able to comb through the data easily, while determing key factors for each school, district, and students. Statistics like Average Math Score, School ranking by Spending, etc., were found by utilizing differing functions within pandas. 

## Analysis and Conclusions: 
The dataset I worked with encompasses 15 schools split between charter and district, and has a total of 39170 students between them. The total student average reading score is 81.87, which is roughly 4% higher than the average math score of 78.98%. It was also determined that the passing rate in reading was at 85.81% while the math passing rate was at 74.98%, and an overall passing rate of 65.17%. This indicates that students are scoring higher in reading than in math. 

The next step in our analysis of these schools is our school summary which shows that 7 of our schools are district level, and the remaining 8 are charter level. Our student totals range from 427 (Holden High) to 4976 (Bailey High). Based on this summary table it is a strong conclusion that more students attend District Level schools than Charter Schools. 

I also looked through the total budget of each school in the same summary table as above. The high was once again held by Bailey High School with $3,124,928.00, while the low was also Holden High at $248,087.00. This budget helps reflect the conclusion above because it means that District Level Schools receive more funding to keep up with there larger student numbers. 

Our next area to look at is which schools are in the top 5 of our dataset based on overall passing rate, and which are the bottom 5. Based on overall passing rate, Cabrera High School holds the honor of being our top school, while Johnson High School is our lowest school. This is interesting to note due to where the budgets for these schools are. Johnson High School has the second highest number of students at 4761 and second highest budget at $3,094,650.00, but they are the worst performing school. While Cabrera High School sits roughly in the middle at 1858 students, and a budget of $1,081,356.00. 

Now, I took a look through each grade associated with High Schools. Interestingly enough, Holden High School holds both the highest average math score and highest average reading score when compared to the other schools. They sit at 85.00% for average math score for 11th graders, and roughly 84.70% for average reading score for 12th graders. However, according to our top and bottom schools, Holden appears on neither which means they sit middle of the pack. 

Finally, I created summaries for scores by school spending, school size, and school type. Surprisingly, when looking through our analysis of the spending scores, 6 out of the 7 schools that were spending $630 or more per student, did not have above a 60% overall passing rate. While the each of the schools that spent $630 or less per student were all above an 89% passing rate. In fact, the metrics fro average math score, average reading score, % passing math, and % passing reading all decreased the more a school spent per student. But when looking at school size in regards to school, it was actually the middle tiered schools that were doing the best in almost every metric. However, the largest schools were still doing the worst in regards to all metrics. And lastly, we can see through our school type summary that Charter schools do much better in regards to these metrics as well. 

Our final conclusions from this analysis are that Charter Schools while smaller, tend to do much better in regards to average math score, reading score, and overall passing rate. The other conclusion we came to was that even though certain schools have larger budgets, and spend more per student, that does not directly impact how well the students will do in our metrics. If anything it shows that the larger the school budget is and spending per student, the worse the school is doing. 

All code was done using examples from in class lectures from UO Data Analytics Bootcamp. Import Warnings and the code to ignore deprecated functions was given by Thomas Tellner in Slack to help make the code look clean. 
