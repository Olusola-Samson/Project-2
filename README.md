# project-2
 Data analysis and visualization of compiled tweets
## By (Olusola Samson)

## Dataset

> **This is a Twitter account dataset from WeRateDogs which has tweets from the account since 2017
which is made up of 3 different datasets Our focus will be on how well we can gather data and clean them.**
>For the First Dataset:**There are 2356 observations and 17 fields with of which most are categorical in nature and the rest are dates and numerical data.**
>For the Second Dataset :There are 2354 and 3 fields which are all numerical
>For the third Dataset:  There are 2075 and 12 fields Most of which are strings(categorical data) and booleans with few being numerical
Wrangling steps involve:
>dropping rows
>Merging datasets 
>Removing retweets from the merged datasets

Issues that were cleaned
* the timestamp contains both the date and time making it messy
* 3 columns with empty spaces are filled up with the mean
* some column have no importance in the so they are dropped
* making sure all three datasets correlate i.e they all have the same order of rows.
* Text that have retweets need to be removed
* the datasets are numbered diffrently ,therefore they are queried with the tweet_id of the lowest numbered dataset
* ratings that are outside the range i.e those above 30 are dropped


## Summary of Findings
After cleaning and merging the 3 datasets ,some observations / insight were also made from the visualization :
### Insights and Conclusion
* insight 1:   **we can infer that the higher Ratings a tweet gets the more likes it has , as we can see that those tweets with ratings between the range of 12 and 14 have the highest number of likes and those less than 10 have an average number of likes with the likes peaking between 4 and 8 due the past standards of the ratings which were mostly under 10 but as the channel's increased the more irregular their ratings got.**

* insight 2: **Also the same thing can be said for the retweets as more people tend to retweet a post depending on the rating given which also peaked between 12 and 14 but the diffrence lies in the fact that the tweets with lower ratings do not get as much retweets as likes.**

**Conclusion: It's safe to say that the effect the ratings have on the amount of retweets and likes are not that diffrent .
which is the fact that it generally affects them both greatly.**
    
