# pandas-challenge

Many thanks to Roberto Salazar (rsalazar4) from AskBCS for debugging help. 


This script merges and analyzes two data sets, aggragates that data, and presents the data in various new dataframes on which analysts are able to draw conclusions. 

The data is repackaged into two groups: District-wide data, and Per School data. 
Various data parsing and cleaning operations are used to present the data in a meaningful way.

# PyCity Schools Analysis
---

### Overview
This data looks at the high schools in the school district. There are  15 schools; 8 Charter and 7 District schools, at which over 39,000 students attend. The high schools have a combined budget of over $24.6M. Unforunately, the district's high schools are lagging behind in students passing both math and reading, at only a 65% rate. While the respective passing rates for each subject are higher (74.98% and 85.81%), the overlap is not as wide as we would like to see.

### Funding Discrepancies

As we look at the schools a little more closely, we can see that the schools with the highest budgets are all district-run schools. No charter school has a budget over $1.32M, while no district-run school has a budget *under* $1.75M. Along the same vein, the total students and budget per student tell a similar story. The district schools all have more students and more per student spending than their charter school counter parts. 

Since we are concerned with student success and return on investment, we will look at the schools' overall passing rates through the lens of per student funding.

### Passing Rate Discrepancies

No charter school has an overall passing rate below 89.89%, while no district school has an overall passing rate *above* 54.6%. Conversely, no charter school has a per student budget of over $638, which when ranked against district schools is good enough for 6 out of 8. We see consistent outperformance of their respective budgets from charter schools in this district, while consistent underperformance from district schools. 

**In fact, we see that as per student budget increases, overall performance decreases, which goes against all conventional wisdom that investing more money into our schools yields positive results in student outcomes.**

### Class Size Could Play a Role 

We also see that school size seems to play some role in student success, as all charter schools are smaller than their district counterparts. This makes sense as it has been shown time and time again that smaller class sizes are good for students, as they lead to more one on one teacher to student interaction and tutoring. 

### Take-aways 

We see that funding seems to play an inverse role in this district's high schools, while class size tends to follow a normal trend. The data in tables below will provide some additional context for the observations in this rundown, as well as show how the data was parsed. 