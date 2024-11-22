# Do tweets with extreme sentiment about OpenAI and Chat-GPT receive more engagement compared to neutral sentiments?


*The project aimed to investigate the relationship between sentiment and engagement on Twitter, specifically focusing on tweets related to OpenAI and ChatGPT after the release of ChatGPT-4.*

*The analysis revealed a weak correlation between sentiment (positive, negative, neutral) and engagement metrics (likes, retweets, engagement per follower). This suggests that extreme sentiment might not be the primary driver of engagement for tweets about OpenAI and ChatGPT during the studied period, potentially influenced by sensationalism surrounding the release of ChatGPT-4.*

*Our group utilized advanced Python techniques and data analysis methodologies, such as pre-processing, feature engineering, sentiment analysis, and data visualization, all within AI4ALL's AI4ALL Ignite accelerator program.*


## Problem Statement <!--- do not change this line -->

The motivation for this project, why it is relevant, and what its impacts are.

*As AI technologies like Chat-GPT 4 become integrated into our daily lives, understanding public perception of those technologies during periods of heightened attention to them is essential. This project examines whether extreme sentiment (positive or negative) further influences engagement on a popular and sensationalized topic like Chat-GPT. By exploring this link, the research challenges the assumption that extreme sentiment drives higher interaction and encourages a shift away from sensationalism in tech reporting and social media. These findings can help platforms like Twitter refine their algorithms to prioritize informative and balanced content during major product launches. Our project promotes a more thoughtful approach to technology adoption and encourages critical evaluation and thoughtful data collection.*

## Key Results <!--- do not change this line -->

Primary Findings:

1. *Weak Correlation Between Sentiment and Engagement*:
   - Sentiment expressed in tweets (neutral, positive, or negative) showed little to no correlation with likes and retweets.
   - Analyses using Pearson’s coefficient, linear regression, and visualization methods consistently indicated poor predictive power of sentiment for engagement.
     
2. *Influence of Sensationalism*:
   - The dataset was collected shortly after Chat-GPT 4’s release, during a period of high public interest and media hype.
   - Engagement may have been driven by the novelty of the technology rather than by the sentiment of the tweets.

3. *Insights from Sentiment Analysis*:
   - Words associated with specific sentiment categories offered insights into user opinions and concerns about Chat-GPT.
   - Despite multiple adjustments, sentiment prediction models like logistic regression and random forest classifier reached 75% accuracy at most, reinforcing the need for a better dataset for sentiment analysis and thus, sentiment-engagement prediction.
  
4. *Need for a More Elaborate and Comprehensive Dataset*:
   - The confidence scores for the sentiment labels were inconsistent suggesting the unreliability of the sentiment data.
   - The dataset was also unbalanced which affected the model training.
   - The tweets in the dataset may not be representative of Twitter's algorithm and public opinion on AI 


## Methodologies <!--- do not change this line -->

To achieve our research objectives, we employed a multi-step methodology involving data collection, preprocessing, and advanced analysis techniques:

1. *Data Collection and Preprocessing*:
   - Downloaded Kaggle dataset of tweets related to Chat-GPT 4, which included tweet texts, sentiment labels, and engagement metrics like likes and retweets.
   - Cleaned and processed the data by handling missing values, removing outliers, and preprocessing text for analysis.

2. *Feature Engineering*:
   - Created custom metrics such as "engagement" (sum of likes and retweets) and "engagement_per_follower" to provide deeper insights into user interactions.

3. *Exploratory Data Analysis*:
   - Analyzed data distributions, calculated correlation coefficients, mutual information scores, and pearson coefficients, and visualized relationships between sentiment and engagement using scatter plots, box plots, and heat maps.
  
4. *Machine Learning Models*:
   - Performed log transformations of target features
   - Applied Linear Regression (sentiment->engagement) and Logistic Regression (engagement->sentiment) to evaluate the relationship between sentiment and engagement
   - Assessed model performance using metrics like R-squared and MSE for regression models and precision, recall, and F1-scores for classification models.

6. *Sentiment Analysis*:
   - Used TF-IDF vectorizer to vectorize pre-cleaned tweet text data
   - Leveraged pre-existing sentiment labels to train a sentiment analysis model to categorize tweets into positive, neutral, or negative labels
   - Compared the accuracy and cross-validation scores between Logistic Regression (unbalanced, balanced by undersampling and oversampling) and Random Forest Classifier models
   - Determined the most influential words from each sentiment category to better understand the model's prediction process.

7. *Data Visualization*:
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
