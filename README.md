# Project Title: Social Media Data Analysis and Hate Speech Detection

Basic Machine Learning to Clean, Pre-process, Visualize and Analyse data from Tweets and followed by detection of abusive and non abusive tweets

Description: This project focuses on analyzing social media data to optimize engagement strategies and detect harmful content. Using Python, the project involves preprocessing, visualizing, and analyzing Twitter (or similar) data to provide actionable insights and detect abusive language. The techniques applied include text preprocessing, feature extraction using TF-IDF, and visualization to understand tweet characteristics and interactions.

Summary
This project aims to enhance social media strategies and ensure content safety by analyzing tweet data. Key techniques include natural language processing (NLP) for text cleaning and feature extraction, and data visualization for understanding tweet lengths and interactions. The project identifies tweets containing abusive or hate speech using a custom list of terms. This solution can significantly impact businesses by improving content moderation and engagement strategies, ensuring that social media campaigns are both effective and safe.

Solution
Business Impact: Enhanced Engagement: By analyzing tweet characteristics such as length and content, the project helps in understanding what type of content drives more engagement, thus optimizing social media strategies.
Content Safety: The ability to detect and flag tweets with abusive language protects the brand’s reputation and ensures compliance with content policies.
Data-Driven Insights: Provides actionable insights based on data analysis, aiding in making informed decisions to enhance client reach and engagement.

Benefits:
Improved Content Strategy: Identifying successful tweet attributes and engagement patterns helps in crafting better social media posts.
Effective Moderation: Automatic detection of harmful language ensures timely intervention, safeguarding brand integrity.
Informed Decision-Making: Data-driven recommendations support strategic planning for social media campaigns.

Approach
Data Loading and Preprocessing:
Load Data: Imported tweet data from a CSV file.
Preprocessing: Cleaned tweets by removing punctuation, tokenizing, removing stopwords, and applying stemming and lemmatization.

Feature Extraction:
TF-IDF Vectorization: Converted text data into numerical format using TF-IDF to capture the importance of words in tweets.

Visualization:
Distribution Analysis: Plotted histograms to show tweet length distribution.
Scatter Plots: Analyzed the relationship between word count and unique word count.
Abusive Content Detection: Flagged tweets containing abusive words and visualized the distribution of abusive vs. non-abusive tweets.

![image](https://github.com/user-attachments/assets/1752aa6f-2c11-4a14-bc4a-930846b282d1)


Hate Speech Detection:
Custom Dataset: Created a list of abusive terms for detecting hate speech in tweets.
Text Matching: Implemented a function to check for the presence of these terms in the tweets, marking them accordingly.

![image](https://github.com/user-attachments/assets/a15fd222-aac8-4ddf-9e82-8bf033f8b254)

Tools and Techniques:
Python Libraries: pandas, nltk, sklearn, matplotlib
Techniques: Text preprocessing, TF-IDF vectorization, data visualization, custom keyword matching
Dataset Source : Ebuka456
