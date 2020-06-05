# (Ford GoBike System Data Exploration and Explanation: Type of Users)
## by (Caleb Manske)


## Dataset

> Looking at Bay Wheels's trip data for public use in the years of 2018 to 2019. Find dataset here: https://www.lyft.com/bikes/bay-wheels/system-data
    
Please reference: 
- ford-gobike-data folder (keeps cvs.zip from website)
- exploration_template.ipynb
- slide_deck_expl.ipynb (for explanation)
- slide_deck_expl.slides.html (html slideshow)
- df_clean.csv (clean data combine)
- output_toggle.tpl (to make the slides on slide_deck_expl)
- raw_combine.csv (pre-cleaned data combine)



## Summary of Findings

> **Univariate Exploration:** I made a small transformation to see what the with and without outliers of time look like. I had a hard time reading the first plot for hours. The user is most likely to be using an app on a cell phone, being s subscriber, and not using a bike for the whole commute.  We also found that starting location and ending location is not very far and is near the same place.

> **Bivariate Exploration:** We find each month and day is radically different for customers and subscribers.  Customers are more likely to use at a December than January, and is almost a linear relationship as month increases, presumably because it also gets warmer.  We find that weekends are not utilized that much for subscribers. We can almost imply that customers are more likely to be using this service for leisure and fun based on these many graphs and data combined.

> **Multivariate Exploration:** The pattern is very similar among subscribers and customers with rising and lowering in cycles. The peaks might be the difference between weekend use and weekday use as that was evident earlier in a prior graph. Interestingly this graph points out big spikes in a month.  In the Customer's timeline: With only customers analyzed, we find that month's 9 and 10 have less point like peaks compared to the whole dataset combine. However, this does not mean that these peaks are less in duration minutes used but are actually quite the contrary. They reach around a height of 35 minutes compared to the earlier graph which was between 19-20 of a peak. This is also the same case for month 2, 3, 5 and 6.  In the subscriber's timeline: With only customers analyzed, we find that the values in general are much lower including the high peaks. The max is around 12 - 13 minutes. Interestingly, there is no large beginning spike and decline for the first month as shown in the whole and customer's first month. Month 11 is also radically different when it is just subscribers.  This graph like matrix makes sense. As already established, most do not use the bike share for all of the trip. But we find that the distance between those who use the whole way and not, are nearly the same in distance length. And it would make sense that those who subscribe and given a choice to use for the entire trip would not opt out. Those who subscribe use this as a need rather than a desire to get to a place. Customers use this as a fun trip and will use other means necessary if given.  We also find customers again, would use this bike service on their non-working day as leisure especially at a longer time frame.



## Key Insights for Presentation

> There are distinctions between subscribers and customers. Subscribers and customers have a very different life and workstyle.  Subscibers are more likely to use for workday realted purposes while customers more likely to use for fun.  The time of day will correlate with a specific month based on the heat map graphs.  Also as noted earlier, the user was most likely not to use the bike for the entire commute, but subscribers will not avoid not use for the entire trip.