# What-Are-People-Sayin-About-Instagram-Lite

In the beginning , I used RSelenium to scrape the Google Play Store reviews for Instagram Lite to demonstrate how the package can be used to automate browser behavior. Its taken longer than I had initially planned to do this follow-up on the analysis of that data. But better late than never. So in this analysis I will do some exploratory work and some text mining to look at questions such as:

•	How have IG Lite reviews been trending?
•	What are prevalent topics in the Google Play reviews about IGLite?
•	For words with negative sentiment, why are people feeling negatively?
•	What are the most prevalent keywords in the set of reviews?

The main libraries that I will use to do this analysis are udpipe for applying the language model used to develop part of speech tagging, BTM to construct the Biterm model, and textrank / wordcloud to do keyword extraction and make the wordcloud. Both udpipe, BTM, and textrank are part of the Bnosac NLP ecosystem.

The codeset is attached in the .docx file in this repository
