# Do tweets with extreme sentiment about OpenAI and Chat-GPT receive more engagement compared to neutral sentiments?


*The project aimed to investigate the relationship between sentiment and engagement on Twitter, specifically focusing on tweets related to OpenAI and ChatGPT after the release of ChatGPT-4.*

*The analysis revealed a weak correlation between sentiment (positive, negative, neutral) and engagement metrics (likes, retweets, engagement per follower). This suggests that extreme sentiment might not be the primary driver of engagement for tweets about OpenAI and ChatGPT during the studied period, potentially influenced by sensationalism surrounding the release of ChatGPT-4.*

*Our group utilized advanced Python techniques and data analysis methodologies, such as pre-processing, feature engineering, sentiment analysis, and data visualization, all within AI4ALL's AI4ALL Ignite accelerator program.*


## Problem Statement <!--- do not change this line -->

The motivation for this project, why it is relevant, and what its impacts are.

*As AI technologies like Chat-GPT 4 become integrate in our daily life, understanding public perception during periods of heightened attention is essential. This project focuses on examining whether extreme sentiment (positive or negative) further influences engagement on a popular and sensationalized topic like Chat-GPT. By exploring this link, the research challenges the assumption that extreme sentiment drives higher interaction and encourages a shift away from sensationalism in tech reporting and social media. These findings can help platforms like Twitter refine their algorithms to prioritize informative and balanced content during major product launches. Our project promotes a more thoughtful approach to technology adoption and encourages critical evaluation over impulsive reactions to hype.*

## Key Results <!--- do not change this line -->

Primary Findings:

1. *Weak Correlation Between Sentiment and Engagement*:
   - Sentiment expressed in tweets (neutral, positive, or negative) showed little to no correlation with likes and retweets.
   - Analyses using Pearson’s correlation, linear regression, and visualization methods consistently indicated poor predictive power of sentiment for engagement.
     
2. *Influence of Sensationalism*:
   - The dataset was collected shortly after Chat-GPT 4’s release, during a period of high public interest and media hype.
   - Engagement may have been driven by the novelty of the technology rather than by the sentiment of the tweets.

3. *Insights from Sentiment Analysis*:
   - Most tweets expressed neutral sentiment, followed by positive and negative sentiments.
   - Words associated with specific sentiment categories offered insights into user opinions and concerns about Chat-GPT.
   - Predictive models like logistic regression and random forests performed poorly, reinforcing the weak correlation.


## Methodologies <!--- do not change this line -->

To achieve our research objectives, we employed a multi-step methodology involving data collection, preprocessing, and advanced analysis techniques:

1. *Data Collection and Preprocessing*:
   - Downloaded Kaggle dataset of tweets related to Chat-GPT 4, which includied sentiment scores and engagement metrics like likes and retweets.
   - Cleaned and processed the data by handling missing values, removing outliers, and standardizing text for analysis.

2. *Feature Engineering*:
   - Created custom metrics such as "engagement" (sum of likes and retweets) and "engagement_per_follower" to provide deeper insights into user interactions.

3. *Exploratory Data Analysis*:
   - Analyzed data distributions, calculated correlation coefficients, and visualized relationships between sentiment and engagement using scatter plots, box plots, and heatmaps.

4. *Sentiment Analysis*:
   - Leveraged pre-existing sentiment scores and constructed a sentiment analysis model to categorize tweets into positive, neutral, or negative sentiments.
   - Extracted influential words from each sentiment category to better understand public opinion.

5. *Machine Learning Models*:
   - Applied Linear Regression, Logistic Regression, and Random Forest Classifier to evaluate the relationship between sentiment and engagement.
   - Assessed model performance using metrics like R-squared for regression models and precision, recall, and F1-scores for classification models.

6. *Data Visualization*:
   - Generated detailed plots and charts to effectively communicate findings, emphasizing the weak correlation between sentiment and engagement.


## Data Sources <!--- do not change this line -->

*Comprehensive Sentiment Analysis Dataset: [Kaggle Dataset](https://www.kaggle.com/datasets/evilspirit05/tweet-gpt)*

## Technologies Used <!--- do not change this line -->

List of the technologies, libraries, and frameworks used in the project.

- *Python*
- *pandas*
- *NumPy*
- *Matplotlib*
- *Seaborn*
- *Scikit-Learn*


## Authors <!--- do not change this line -->

*This project was completed in collaboration with:*
- *Banibe Ebegbodi ([bani.ebegbodi@gmail.com](mailto:bani.ebegbodi@gmail.com))*
- *Viktoriia Sokolenko ([viktoriia.i.sokolenko@gmail.com](mailto:viktoriia.i.sokolenko@gmail.com))*
