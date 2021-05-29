<b><i>Intro</i></b> - Many people and places around the world are still seeing the effects of COVID-19 after over a year of dealing with the virus.  There are many ways to find information about COVID-19 such as websites, social media, word of mouth, and news.  There is a mix of true and false pieces of information all over the place about this virus and vaccines that will help prevent people from getting it.

The Centers for Disease Control and Prevention (CDC) defines COVID-19 as “a respiratory disease caused by SARS-CoV-2, a new coronavirus discovered in 2019.  The virus is thought to spread mainly from person to person through respiratory droplets produced when an infected person coughs, sneezes, or talks. Some people who are infected may not have symptoms. For people who have symptoms, illness can range from mild to severe. Adults 65 years and older and people of any age with underlying medical conditions are at higher risk for severe illness” (CDC, 2021).

COVID-19 vaccines have been a hot topic at the end of 2020 and into 2021.  Finding ways to communicate the correct information with people all over the world is tough.  There is so much information that it is hard to differentiate what is true or not.  One way to identify and communicate with people is through social media websites where companies and individuals post, share, and reply to posts.  For instance, companies can use Twitter to Identify what other companies, people, and news organizations are tweeting and retweeting about and target them with specific information to tweet.  This could include where to get vaccinations, facts about vaccines, vaccines that are available, and other COVID-19 discussions. (based on the Twitter Tweets Report.docx)


<b><i>Tools</i></b> - R, CSV, PowerPoint, Word

<b><i>Tools</i></b> - The dataset I used is Twitter tweets that are not included in retweets.  Twitter only allows a person to download up to 18,000 records at a time every 15 minutes.  Without a Twitter subscription, the data only goes back 8 days.  There are a lot of fields that Twitter stores information for.  The fields I mainly used to review the tweets are screen_name, text (tweet), source (what device was used to tweet), location, followers_count, friends_count, and account_created_at.  

<b><i>Methods/Evaluation/Techniques</i></b> - I cleaned the almost 18,000 records of Twitter tweets, summarized the data, created charts/graphs, completed a word cloud, and utilized machine learning in sentimental analysis.

<b><i>Conclusion</i></b> - Overall, there are many ways to analyze Twitter tweets.  Cleaning the data in Twitter tweets can take time as there can be so many different variations of words.  Throughout the last four weeks, it has been interesting to see how the various tweet word utilizations have changed when analyzing the keywords “COVID Vaccine”.  After reviewing the sentimental analysis, I found that there were more negative words than positive words.  Also, there were various screen names that tweeted about COVID within the last 8 days which included consumers, bots, and individuals.

<b><i>Navigation</i></b> - 

<b>COVID_Vaccine_Twitter_Tweets.Rmd</b> is the main R file on the GitHub website

<b>TwitterTweetsDataset.csv</b> is the file that is uploaded into the rmd file 

<b>Twitter Tweets Presentation.pptx</b> is a PowerPoint presentation

<b>Twitter Tweets Report.docx</b> is the final report
