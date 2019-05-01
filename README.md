# Youtube Video & Channel Data Analysis
**IS590PR Final Project**<br>
By Pin-Huey Chiang, Hung-Yi Lin

Youtube has played an important role in our daily life. People spend more time on watching Youtube videos than on TV these years. Youtuber has became one of the most popular career choice for young generations. If a teenager loves to watch entertainment type of videos, such as PewDiePie and Logan Paul, he may also dream of becoming a top-ranking Youtuber who films entertainment videos. This raised some research questions:
* Is filming entertainment channel a valuable decision for him/her?
* If he/she reach the goal and become the top-ranking Youtuber, what is the condition he/she must know.

## Hypothesis
### Part 1
* Entertainment videos will likely to trend more than other types of videos such as comedy, music, fashion and knowledge in the United States. 
* Among top-ranking U.S. Youtubers, it will be more profitable to operate the entertainment type channel than other types of channel such as comedy, music, fashion, knowledge

### Part 2
* Top U.S. Youtubers will have more trending videos than other Youtube channels
* If you own a top-ranking Youtube channel in the U.S., you can make a big profit

## Method:
### Web Crawling of Top YouTube Channels 
This web crawler collects the top 250 US Youtube channel information from SocialBlade.com based on the rankings of socialblade grades, total subscribers and total video views. The datasets include 19 columns such as US ranks, number of subscribers, number of video views, average daily/monthly/yearly earnings, and so on.

### Trending Video Analysis
The trending videos is decided by YouTube trending system based on view counts, the rate of growth in views and the age of the video. This means that even if one video meets all the criteria, it does not mean it will definitly enter Trending. The Trending system tries to choose videos that will be most relevant to their viewers and most reflective of the broad content on the platform. Therefore, this analysis allows us to get an insight of what types of videos Youtube thinks viewers would want to see the most, and reflects to the events that happened in the given time.

### Top Ranking YouTube Channel Analysis
This analysis analyze the information of Top 250 US YouTubers based on the number of subscribers or number of views, which gives insights of the profit the top Youtubers can earn.

    + In this analysis, we only collects the Top Youtube channels in the United States.
    + In this analysis, we did not exclude the official channels.
    + This analysis uses the categories that defined by Youtube, which includes Auto & Vehicles, Education, Entertainment, Food, Music, and so on. Youtubers can choose what kind of categories the video belongs to before uploading them to the platform in their video management webpage.
    

## Result
### Part 1
1. Compare to other types, entertainment videos have the most trending videos during the data captured period (from 2017-11-14 to 2018-06-14). However, we cannot directly say filming entertainment videos will definitely make your videos trend more. We need to calculate the proportion of "num of trending videos / num of videos to know the performance of entertainment videos. Since we do not have the data of total uploads, we chose to look at the average of views/likes/dislikes/comments in per trending video, and average time a video need to spend from publish to upload. The outcome indicated that entertainment videos is one of the video type that audiences can attract more audiences to watch.
2. Among the top 250 US Youtube channels, 65 of them are entertainment channel. Some of the channels earn much more money than others, while some are lower than average. The large gap makes the average earnings not as high as expected. However, when we look at **all 32** the categories, entertainment video is in the **top 5 categories** that can earn most profits. Thus, we can say that entertainment type of Youtube channels has a lot of potentials if you want to earn money, but it is also very competitive to become the Top YouTubers in this category.

### Part 2
1. According to the result, Top 250 US YouTubers, which is **0.001%** of the total YouTubers in the world, account for **15%** of the trending videos in the given period. This showed that people pay more attention on Top YouTuber's video than others. If a person would like to become a YouTuber how they attract people to watch their films is one of the most important tasks. 
2. We found of the there is a big income gap between the top 10 entertainment YouTubers and the last 10 entertainment YouTubers. To have a better understanding in each categories' earning difference, we came up with a formula to obtain the concept of earning distribution of top-ranking channels. The higher the indicator is, the larger earning gap will be. 
<img src="https://github.com/gillian850413/Final_Project/blob/master/image/formula.png" width="600" height="150"/>

3. Last, we realized that YouTuber is an unpredictable and unstable job. Take Justin Timberlake's channel as an example. Although he is not a professional YouTuber, he can still earn money from every click per cost of his videos and the advertisement. We found out that his last video is uploaded two months ago. According to Socialblades' channel statistic, the estimated channel Yearly Income is $83 - $1.3K, while other YouTubers with similar number of subscribers can earn millions of dollars per year with their channel. Socialblades estimates the daily income per channel based on the increase or decrease of video views and subscribers, than calculate the yearly income by multiplying 365. This shows that when a channel is inactive for a while the growth of video views and number of subscribers will sharply drop, which will have a huge impact on the earnings of a channel. Therefore, if people wants to become successful in this career, they need to keep your channel active by uploading the videos frequently. 

## Summary
### Possible factors to become a successful Youtuber:
1. Youtube channel types people like to watch the most
2. Have many subscribers and video views 
3. Youtube channels that have more trending videos

### Five measurements of whether a Youtube channel is successful:
1. Amount of money they earned
2. Number of subscribers
3. Number of video views
4. Number of trending videos
5. Youtube channel type

### Conclusion
This analysis shows that entertainment videos are one of the most popular types for Youtube viewers. However, it is also pretty competitive to make the big profit by filming entertainment type videos since there are large amount of entertainment channels in YouTube now.

Top-ranking Youtubers are extremely rich. However, only a few people can hit the high rank and their channels includes disproportionate trending videos. On top, the earning distribution of top-ranking Youtubers is strongly right skewed, which shows a large earning gap even in the industry.

## Limitation
* The dataset only includes 8 month data, we may need a larger time period data to have a better analysis
* This dataset only includes Top 250 Youtube channel, which may be hard for generalization analysis

## Future Work
* We can collect not only the Top ranking YouTube channel information, but also the channel information that are not included in the chart for a more in-depth comparison between the well-known YouTubers and other normal YouTubers
* We can compare the data from other countries and see whether the favorite type of videos and profit earnings will differ from country to country. 

## Source
### Dataset Source:
1. [SocialBlade](https://socialblade.com)
2. [Trending YouTube Video Statistics](https://www.kaggle.com/datasnaek/youtube-new/kernels)
### Other Sources:
1. [YouTube categories](https://creatoracademy.youtube.com/page/lesson/overview-categories#strategies-zippy-link-2)
2. [YouTube trending video definition](https://support.google.com/youtube/answer/7239739?hl=en)
3. [Justin Timberlake SocialBlade Statistics](https://socialblade.com/youtube/user/justintimberlake)

## Division of Work
1. Hung Yi Lin: Top rank Youtube channel analysis, Poster, Doctest
2. Pin Huey Chiang: Web Crawling, Trending video analysis, Readme, Poster, Doctest
