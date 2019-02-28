We collected data from espn cric info 
we use the query interface editor to get different sort of data. we cleaned those for example there were missing values as well as invalid values like * 
in runs and High scores. we removed unneccesary columns based on our assumptions.

for batting data , we collected last 5 years data for indian batsman and collected the last two matches as target for those records.
we used corerelation between variables in order to get the weightage .
we did the same thing for australia batting statistics too
for bowling data also we collected last 5 years data for indian and australian players and tried to predict the corelation with thier latest stats.
For team wise data we found venue and toss is not providing any importance towards the winning. we collected the data and used feature selection algorithm to find those .

For every step  we calculated the weigtage for each played based on the correlation coeffecients.
For a team we added those individual attributes for batting weightage , bowling weightage and inning wise.






