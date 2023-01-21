# The-Traitors-UK - A Twitter Sentiment Analysis

# What is The Traitors UK?
'The Traitors' is a tense psychological adventure competition where 22 strangers are moved into a castle in the Scottish Highlands to complete a series of challenges and missions together as a team. The catch, however, is that amongst the loyal contestants hoping to win a cash prize of up to £120,000, three traitors are secretly lurking, sabotaging their efforts and picking off contestants one by one. In the ultimate game of detection, backstabbing and trust, the loyalists must root out the traitors amongst their ranks in order to win or risk losing everything.

# The purpose of this project
1.	Mine tweets from Nov-Dec 2022 using the keyword #TheTraitorsUK
2.	Transform the data from unstructured to structured, by using text cleaning and natural language processing (NLP) methods.
3.	Create a dashboard from Tableau to visualise results.

# Actions Taken

1. Data Gathering: I scraped tweets using the SN (Social Network) Scrape library. A total of 5152 Tweets were extracted for Nov-Dec 2022.
2. Data Exploration
3. Data Cleaning and Pre-processing: For this task, I used Regular Expressions (RE), Natural Language Toolkit (NLTK) and NeatText libraries to clean and pre-process the data, which involved
-	Removal of hashtags, @mentions, urls, emojis, punctuation marks, whitespaces etc.
-	Removal of Stopwords
-	Word Tokenization
-	Lemmatization (to draw meaning)
4. Sentiment Analysis: This is derived from the polarity score
5. Dashboard Creation: I exported the Python data frame to Excel and built the Dashboard in Tableau

# Results
Since the show had me captured, I was curious to know how the Twitter community found the show. It came as no surprise that Wilf was the most popular contestant. He was the ultimate traitor after all. Based on the sentiment analysis, the opinions are more positive than negative.
# User Implications
This type of analysis can benefit businesses in any context. Analysing Twitter perceptions can help managers to understand their customers better and make data-driven decisions.
