# Ukraine-Russia on Twitter: Network Analysis of Influencers and Bots
This Project was done as coursework for Social Media Analytics course taught in the Spring Semester for UT Austin's MS Business Analytics Program.

## Project Description
This project aims to understand the narrative of the Russia-Ukraine propaganda network on Twitter by analyzing influencers and bots. The project begins with the collection of 13k tweets using nine hashtags. A bot detection model was developed and trained using Tweepy library and a random forest classification model. The bot model returned an accuracy of 77.7% on the test set. The analysis showed that 18.1% of tweets were produced by accounts classified as bots, and 17.2% of users in the network were classified as bots.

Further analysis was conducted on the influencers and bots. It was found that the network was self-sustaining, suggesting that it is driven by both human and bot accounts. The topic modeling identified three main topics - news, general war, and Russian embassy. The top 15 influencers were analyzed, and it was found that none of these accounts appeared to be bots, and none of them originated from Russia or Ukraine.

The conclusion suggests that the prevailing narrative regarding Russian bots is not entirely accurate, and targeting influencers or bringing more influencers into the network may not be an effective strategy. Instead, the project recommends improving the bot detection software by supplementing it with named entity recognition, frequency of hashtags/mentions, and additional verification using a reCaptcha or other bot-prevention software test. Additionally, enhancing the search engine using topic modeling to aggregate similar hashtags is recommended.

Overall, the project used Tweepy to scrape tweets, LDA for topic modeling, and NetworkX for network analytics. The project provides a comprehensive analysis of the Ukraine-Russia network on Twitter, highlighting the importance of understanding the influence of both humans and bots.
