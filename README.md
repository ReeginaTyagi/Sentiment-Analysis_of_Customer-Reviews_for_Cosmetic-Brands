# -Sentiment-Analysis_of_Customer-Reviews_for_Cosmetic-Brands_from-_Google-Play-Store
In this project, we conducted an extensive sentiment analysis on customer reviews for various cosmetic brands, including Nykaa, Mamaearth, Sugar Cosmetics, Myglamm, Pilgrim, Plum, Mcaffeine, and Juicy Chemistry sourced from the Google Play Store. The primary objective was to evaluate and compare the sentiment expressed in user feedback to better understand customer satisfaction and identify areas for improvement. We began by scraping user reviews from the Google Play Store using google-play-scraper, a Python library for web scraping from Google Play Store. After collecting the data, we performed data cleaning and preprocessing to handle missing values and ensure the textual data was ready for analysis.

Using TextBlob, an NLP library in Python, we analyzed the sentiment of the reviews. TextBlob computes the polarity of the text, providing a sentiment score that ranges from -1 (negative) to 1 (positive). This allowed us to quantify the sentiments expressed in the reviews and calculate an average sentiment score for each brand. Through this analysis, we could identify trends and patterns in customer opinions, highlighting areas where brands are performing well and where there may be room for improvement.

The findings from this project offer valuable insights into consumer perceptions and can guide strategic decisions for product enhancement and customer engagement. By understanding the sentiment behind customer reviews, cosmetic brands can tailor their strategies to better meet customer needs and improve overall satisfaction. This project not only showcases the practical application of sentiment analysis in a business context but also demonstrates proficiency in data scraping, natural language processing, and data analysis using Python and its libraries.
