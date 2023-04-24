# World Cup Kick-Off: A Twitter Snapshot of the First Day
## Project Description & Rationale:

Our overall team’s topic is exploring tweets related to 2022 Qatar FIFA World Cup, from a dataset which added tweets everyday for a period that lasted the entire duration of the game. Thus, for this honors project, I chose to single out the first day of the tournament and dive into what the main topics and sentiments were from that day, particularly with a focus on whether humanitarian rights were addressed in online discourse. My rationale for this section is due to the fact that these human rights violations occurred before the tournament began, with the construction of the stadium and infrastructure needed for an event which hosts over 1.4 million visitors (Qatar 2022). Thus, by looking into the first day when games had just begun, I wanted to explore what users initial reactions and feelings towards the tournament and its host country were prior to being influenced by the actual game.

My research questions include: (1) what were the sentiments on the first day of the tournament, and was there a humanitarian focus, and (2) what were the trending discussions on the first day of the cup, and was there a humanitarian focus? I chose these research questions as I was curious to see what trending topics occurred on the first day of the tournament, and how they may correlate to events happening on that day or prior to such. Additionally, I explored sentiments to see how they might correlate with these trending topics as well.

## Significance: 

This project is important because it helps readers understand the global impact that the world cup has, as well as the gruesome implications it results in. The world cup, as is any giant international event, often results in the discrimination and abuse of marginalized communities who suffer from government negligence due to the capitalist focus on the tournament. Most of these human rights violations happen before the tournament even begins, mostly due to the grueling work conditions that workers face when constructing the stadium. In Qatar specifically, migrant worker abuse is no strange occurrence, as they make up 90% of the work force, known as the kafala system. With international concern regarding the building of the infrastructure needed for the tournament, Qatar did announce major reforms for the kafala system, however actual implementation of many of these claims did not occur (Freedom House).

Part of the this project looks into initial reactions to the cup, and if there was an emphasis on human rights violations, particularly among tweets rated as negative sentiments. This project will help inform readers on whether there was international concern through social media, and potential reasons of why this may or may not be.

## Audience: 

I imagine that people who are fans of the tournament, or even those who passively watch the highlights, would be interested in my project. The world cup is one of the largest structured international events that takes place regularly, thus it draws a lot of attention on both traditional and newer media platforms. The needs of which it would address is a snapshot of how twitter users viewed a tournament which has fundamental geopolitical influence. My project might answer questions such as who were the key countries and players mentioned on the first day, as well as initial thoughts about Qatar being the host country. These opinions most definitely changed throughout the duration of the cup, especially dependent on how the user liked the outcome of the tournament.

## Technical Specifications: 

The main tools that I have used include a mix of different analytical tools such as R/ RStudio, Voyant Tools, and Tableau. The reason I decided to use a mixed methods approach was due to the fact that each of these tools has it’s own strengths and weaknesses. For example, R is great for large datasets, which this one at over 30,000 tweets is. However, it doesn’t perform well when being flexible with it’s visualizations. Tableau is great for time-based data and producing clean and easy-to-understand visualizations, but can be difficult to use when trying to produce computing resources to work with large datasets. Lastly, Voyant is great for identifying patterns within text-based components of datasets, but does not offer much past text-analysis. Thus, by using a combination of these tools I was able to produce comprehensive findings on a variety of types of sub-topics. 

## Data Selection: 

The dataset contains the tweet id, date created, number of likes, source of tweet (device), content of tweet, and sentiment. I did not scrape the data directly from Twitter, but chose a dataset that was already pulled from Kaggle. The dataset included any tweet made on November 20th that included ‘WorldCup2022’. I chose to select this dataset due to its correlation with my team’s project of analyzing the Qatar World Cup throughout the duration of the entire tournament. I cleaned the dataset by removing columns which we unnecessary/ did not relate to the contents of what I was trying to research. This mainly included the column “source of tweet” which included if the tweet came from a user with an iPhone, android, or who was using the website. I also filtered out the data to create two data subsets for positive sentiment tweets and negative sentiment tweets, which I will further explain in my work plan.

## Description of work plan:

I completed a variety of methods to explore this dataset. First, using R, I created a frequency table to explore how many negative, positive, and neutral tweets were in this dataset. However, the creator of the dataset didn’t state what method they used to sort the tweets (such as which package), which is why I decided to explore the sentiments using Vader and Syuzhet. I created a timeline of sentiment scores to analyze how positive and negative tweets might’ve shifted throughout the first day. Additionally, I created a bar chart that explored the frequency of tweets under different sentiment subcategories, such as anger, anticipation, disgust, fear, joy, sadness, surprise, and trust. Lastly, I filtered out the data to create two subsets of just the negative tweets and the positive tweets. From there, I used Voyant tools to create word clouds, one from each sentiment subset, and compared them to see any major differences between the positive and negative tweets on this first day. 

## Findings:

### Research Question addressed: What were the sentiments on the first day of the tournament, and was there a humanitarian focus?

INSERT PHOTO HERE

I first created a frequency table to explore how the dataset categorized negative, positive, and neutral sweets. I found that there was an almost even split between neutral and positive tweets on the first day of the event. However, there was almost half as many negative tweets. Thus, sentiments seemed to be overwhelmingly positive, which is indicative of a focus on the excitement of the actual game rather than the grievances up to the that point. I did choose to do my own sentiment analyses separate from the one included in this dataset, as the author wasn’t transparent in what package or software they used when categorizing the tweets.

### Research Question addressed: What were the sentiments on the first day of the tournament, and was there a humanitarian focus?

INSERT PHOTO HERE

From creating a bar chart using the Syuzhet sentiments analysis, I found that there was a higher number of negative-sentiment tweets than positive ones. This contrasted greatly from my earlier finding, but I recognize that each sentiment analysis method has its own method of categorizing sentiments. In addition, there were nearly equal levels of anger, fear, and trust detected from the tweets. Thus, it seems that which would account for why there were many tweets categorized as neutral. What also surprised me about this finding, is how similar it is to the sentiment chart that analyzed the dataset from the entire tournament. Thus, it can be said that the first day sentiments are indicative of the sentiments throughout the entire duration of the tournament. This surprised me, because I expected users’ views and perceptions to be shifted as major events occurred, but it seems that perceptions stayed consistent from this first day. 

### Research Question addressed: What were the sentiments on the first day of the tournament, and was there a humanitarian focus?

For this timeline, I found that there was very polarizing sentiments and reactions towards the first day of the tournament. The value for sentiment compounds ranged from -0.972 to 0.985, and stayed consistent throughout the entire day. I did notice a slight decrease in negativesentiment tweets in the beginning of the day, but it seems that other than that initial dip that negative tweets stayed pretty consistent. An example of a negative tweet included that of “F*ck Fifa F*ck WorldCup2022 and F*ck Qatar Stick your shambolic and shameful excuse for a World Cup back up your fraudulent a*ess BoycottQatar”, which was rated a -0.949. An example of a positive-rated tweet was “As the WorldCup2022 kicks off today, we wish the very best to Rwandas own and Africas first ever female referee at a mens World Cup RhadiaSalma”, which was rated as 0.802. 

Thus, although there were negative-sentiment tweets my exploration of the dataset found that a lot of boycott Qatar movement were due to suspicion of fraud within the actual tournament, rather than due to corruption of human rights violations. I was surprised to see that much consistent negative tweets, especially because the first day of the tournament is usually stereotyped at being exciting and hopeful as everyone’s team is still in the running. 

### Research Question addressed: What were the trending discussions on the first day of the cup, and was there a humanitarian focus?

INSERT IMAGE HERE
INSERT IMAGE HERE

From the sentiment analyses, I gathered that there was a fairly polarizing and equal split among negative and positive tweets. Thus, I decided to look into the topics of both categories. I created word clouds based on the the top 25 most common words for tweets rated as positive and tweets rated as negative. I found that the word clouds were surprisingly similar, in that they both shared top words that focused in on the game. I did find slight differences, however. The positive cloud mentioned “jungkook", a member of BTS, who performed at the opening ceremony for the tournament. BTS is one of the largest Kpop music groups, so it would make sense that a lot of their fans would tune in and live-tweet for their performance. In the negative cloud, one of the top negative associated words was “ecuador”. I found this pretty interesting considering that Ecuador had won that first game against Qatar and that it was also a top positive topic. I was interested to see that there were no mentions of keywords such as corruption, bloody Qatar, etc. were mentioned. Terms such as “offside” and “goal” suggest that negative-sentiment tweets still continued to center around the sport, rather than critiques of system or host country.

## Conclusion:

In summary, my research focused on analyzing the sentiments and trending topics on the first day of the Qatar FIFA 2022 World Cup, which took place on November 20th. To conduct this analysis, I used the "FIFA World Cup 2022 Tweets" dataset, which compiled any tweet containing the text “WorldCup2022". My findings revealed a polarizing environment on Twitter during the first 24 hours of the tournament, with highly frequent and contrasting sentiments. Surprisingly, there was a lack of attention given to the humanitarian crisis related to the event, and negative sentiment tweets tended to focus on the sport itself rather than FIFA or Qatar. I had anticipated more outrage and calls to action from Twitter users regarding the abusive labor conditions and the significant socioeconomic impact of the World Cup on the people of Qatar. This led me to conclude that simply pushing for policy improvement is not enough, as the promises made by Qatari officials in 2020 fell short. In order to enact meaningful change, there must be public outcry and a willingness to take action. However, based on my analysis, there is still a lot of work to be done regarding education and informing the public in order to reach that point.

## References: 

AI, Tirendaz. “FIFA World Cup 2022 Tweets.” Kaggle, 8 Dec. 2022, https://www.kaggle.com/datasets/tirendazacademy/fifa-world-cup-2022-tweets.

“The Long Shadow of Qatar's Human Rights Abuses.” Freedom House, https://
freedomhouse.org/article/long-shadow-qatars-human-rightsabuses#:~:text=The%20Deadly%20Cost%20of%20World%20Cup%20Construction&text=In%20recent%20years%2C%20it%20has,situations%2C%20and%20wage%2Dtheft.

“Qatar Hosts More than 1.4 Million Visitors during FIFA World Cup™.” Qatar 2022™, https://
www.qatar2022.qa/en/news/qatar-hosts-more-than-one-million-visitors-during-fifaworld-cup.

