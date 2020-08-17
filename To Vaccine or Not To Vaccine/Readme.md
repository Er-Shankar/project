# To Vaccintae or Not to Vaccinate
Work has already begun towards developing a COVID-19 vaccine. From measles to the common flu, vaccines have lowered the risk of illness and death, and have saved countless lives around the world. Unfortunately in some countries, the 'anti-vaxxer' movement has led to lower rates of vaccination and new outbreaks of old diseases.

Although it may be many months before we see COVID-19 vaccines available on a global scale, it is important to monitor public sentiment towards vaccinations now and especially in the future when COVID-19 vaccines are offered to the public. The anti-vaccination sentiment could pose a serious threat to the global efforts to get COVID-19 under control in the long term.

The objective of this challenge is to develop a machine learning model to assess if a Twitter post related to vaccinations is positive, neutral, or negative. This solution could help governments and other public health actors monitor public sentiment towards COVID-19 vaccinations and help improve public health policy, vaccine communication strategies, and vaccination programs across the world.

The data comes from tweets collected and classified through Crowdbreaks.org [Muller, Martin M., and Marcel Salathe. "Crowdbreaks: Tracking Health Trends Using Public Social Media Data and Crowdsourcing." Frontiers in public health 7 (2019).]. Tweets have been classified as pro-vaccine (1), neutral (0) or anti-vaccine (-1). The tweets have had usernames and web addresses removed.

The objective of this problem is to develop a machine learning model to assess if a twitter post that is related to vaccinations is positive, neutral, or negative.

## Variable definition:
* tweet_id: Unique identifier of the tweet
* safe_tweet: Text contained in the tweet. Some sensitive information has been removed like usernames and urls
* label: Sentiment of the tweet (-1 for negative, 0 for neutral, 1 for positive)
* agreement: The tweets were labeled by three people. Agreement indicates the percentage of the three reviewers that agreed on the given label. You may use this column in your training, but agreement data will not be shared for the test set.

