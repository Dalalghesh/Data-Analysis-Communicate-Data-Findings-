# (Dataset Exploration Title)
## by (Dalal Bin Gheshiyan)


## Dataset

   The data consists of information regarding 183412 rides made in a bike-sharing system covering the greater San Francisco Bay area, including 16 features about the area, rider and bike. 

## Summary of Findings

   After Wrangling the data to make an exploration, I found that they are unbalanced considering gender as most of the records belong to males. I was interested to use the age of the rider to make a prediction of the trip duration, so I added the age column using the member birth column,   but there wasn't clear relation between them, as most members' duration ranges are similar.
Furthermore, the female has longer trips than male and customers have longer trips than subscribers.

In addition, about member subscriptions type, I looked for a relation with age or gender, and again age didn't have a special relation with subscriptions type, but male seems to prefer to subscribe rather the be a casual customers. Also,  Unlike I thought, the customer is riding the bike more than the subscriber, with a big difference. 

bike share for all trip column and user type relation show that there is no single Customer shared bike for all trips, and we can conclude that sharing only occurs when a member is a subscriber, and also, with a small percentage.

Finally, males and females prefer not to share a bike for all trips. However, Male is more likely to share a bike for all trip than female. and adding Age, we conclude that younger age is more likely to share a bike with both males and females. 


## Key Insights for Presentation

   For the presentation, I focused on just the main features and features that give a clear relation rather than confusing the readers. 
I start by introducing the ages of members followed by histogram. then duration of a trip, followed by transformed histogram.
Afterward, I introduced the most popular places to start and end a bike trip, using their count plot. 
And finally, I chose Duration, Gender, and User type relation with heatmap representation rather than barplot as it specifies the differences with numbers. 
