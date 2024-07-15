Social Media Sentiment Analysis 
This project performs sentiment analysis and topic modeling on social media data. It includes data cleaning, preprocessing, and visualization to understand public opinion and attitudes towards specific topics or brands.

Data Loading
The script loads two datasets:

twitter_training.csv
twitter_validation.csv
Data Preprocessing
The script combines the datasets and preprocesses the text by:

Converting to lowercase
Removing numbers
Removing extra spaces
Removing punctuation
Data Visualization
The script generates various visualizations:

Sentiment Distribution: Count plot of sentiment categories.
Word Clouds: Word clouds for each sentiment category.
Time Series Analysis
If a 'Timestamp' column is present, the script performs a time series analysis to visualize sentiment changes over time.

Topic Modeling
The script uses Latent Dirichlet Allocation (LDA) to identify common topics in the tweets and displays the top words for each topic.
