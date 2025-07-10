# Python_Milestone

Overview:
This project aims to analyze customer sentiment towards the iPhone 15 128GB model by leveraging customer reviews collected from Flipkart. By using natural language processing (NLP) techniques and data visualization, the project provides valuable insights into how customers perceive the product, what features they praise or criticize, and offers actionable recommendations for business improvement.

Objective:
To extract and analyze at least 300 customer reviews for the iPhone 15 128GB model from Flipkart.
To perform sentiment analysis on the collected reviews to classify them as positive or negative.
To uncover patterns and trends in customer feedback that can inform business and marketing strategies.

Methodology

1. Data Collection:
Customer reviews were scraped from Flipkart using Selenium for web automation and BeautifulSoup for HTML parsing.
For each review, the username, rating, and review text were extracted, ensuring comprehensive data for analysis.

2. Data Cleaning & Preprocessing:
Duplicate and incomplete reviews were removed to maintain data quality.
Review text was cleaned and preprocessed by converting to lowercase, removing special characters and emojis, tokenizing, removing stop words, and applying lemmatization.

3. Sentiment Analysis:
TextBlob was used to assess the sentiment polarity and subjectivity of each review.
Reviews were classified as “Positive” or “Negative” based on a defined polarity threshold.

4. Data Analysis & Visualization:
Various plots and word clouds were generated using Matplotlib and Seaborn to visualize sentiment distribution, rating trends, word frequency, and review characteristics.
Additional analyses, such as the relationship between review length and sentiment, were performed to derive deeper insights.

Key Insights:
The overall sentiment distribution shows the proportion of positive and negative reviews.
Analysis of ratings versus sentiment highlights how numerical ratings align with customer emotions.
Word clouds reveal frequently mentioned topics and themes in both positive and negative feedback.
Insights into review length suggest whether detailed reviews tend to be more positive or negative.

Recommendations:
Based on customer feedback, suggestions are provided for product improvements, customer support, and targeted marketing strategies.
Areas of high satisfaction or frequent complaint are identified to help guide business decisions.

Tools & Libraries:

Selenium: Web automation for data collection

BeautifulSoup: HTML parsing

Pandas: Data manipulation and cleaning

NLTK & TextBlob: Natural language processing and sentiment analysis

Matplotlib & Seaborn: Data visualization
WordCloud: Visualization of frequently used words

Conclusion:
This project delivers a comprehensive analysis of customer sentiment for the iPhone 15 128GB model on Flipkart. The insights and recommendations derived can support business improvements, enhance customer satisfaction, and inform future product development and marketing strategies.

