# YouTube-API_Project1:
![image](https://github.com/Poojamotekar/YouTube-API_Project1-/assets/66488693/f9350f21-0f1a-4da6-82b0-37742f2064b6)

# Exploratory Data Analysing Using Youtube Video Data from Most Popular Channels
# 1. Aims, objectives and background
### 1.1. Introduction
Founded in 2005, Youtube has grown to become the second largest search engine in the world (behind Google) that processes more than 3 billion searches per month. [1]. It is, however, generally a myth how the Youtube algorithm works, what makes a video get views and be recommended over another. In fact, YouTube has one of the largest scale and most sophisticated industrial recommendation systems in existence [2]. For new content creators, it is a challenge to understand why a video gets video and others do not. There are many "myths" around the success of a Youtube video [3], for example if the video has more likes or comments, or if the video is of a certain duration. It is also worth experimenting and looking for "trends" in the topics that Youtube channels are covering in a certain niche.

### 1.2. Aims and objectives
Within this project, I would like to explore the following:

Getting to know Youtube API and how to obtain video data.
Analyzing video data and verify different common "myths" about what makes a video do well on Youtube, for example:
Does the number of likes and comments matter for a video to get more views?
Does the video duration matter for views and interaction (likes/ comments)?
Does title length matter for views?
How many tags do good performing videos have? What are the common tags among these videos?
Across all the creators I take into consideration, how often do they upload new videos? On which days in the week?
Which popular topics are being covered in the videos (e.g. using wordcloud for video titles)?
Which questions are being asked in the comment sections in the videos

### 1.3. Steps of the project
Obtain video meta data via Youtube API for the channels (this includes several small steps: create a developer key, request data and transform the responses into a usable data format)
Prepocess data and engineer additional features for analysis
Exploratory data analysis
Conclusions

### 1.4. Dataset
Data selection
As this project is particularly focused on Youtube channels, I found that not many readily available datasets online are suitable for this purpose. 
I created my own dataset using the Google Youtube Data API version 3.0.

# Data limitations
The dataset is a real-world dataset and suitable for the research. My definition is "popular" is only based on subscriber count but there are other metrics that could be taken into consideration as well (e.g. views, engagement). The top 10 also seems arbitrary given the plethora of channels on Youtube. There might be smaller channels that might also very interesting to look into, which could be the next step of this project.

# Ethics of data source
According to Youtube API's guide, the usage of Youtube API is free of charge given that your application send requests within a quota limit. "The YouTube Data API uses a quota to ensure that developers use the service as intended and do not create applications that unfairly reduce service quality or limit access for others. " The default quota allocation for each application is 10,000 units per day, and you could request additional quota by completing a form to YouTube API Services if you reach the quota limit.

Since all data requested from Youtube API is public data (which everyone on the Internet can see on Youtube), there is no particular privacy issues as far as I am concerned. In addition, the data is obtained only for research purposes in this case and not for any commercial interests.
