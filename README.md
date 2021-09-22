# Smart-Phone-Recommender-Sentiment-Analysis-Chatbot-


The main idea of our project is based on the knowledge of NLTK package from lecture to build a human-AI reacting interface leaning on the result of natural language process sentimental analysis. Given the training data, the algorithm is able to predict the sentiment score for specific brand and model. 


Our outline of the project can be generally divided into 3 steps: 

1-Dataset interpreting and data cleansing. 
2-Sentiment analysis model build and trained based on the extracted and cleansed data.  
3-Recommendation system frame design, including chatbot interaction dialog followed with query generation, prediction and AI advising based on the result of sentimental analysis score. 


 Dataset 

We are using the data from Amazon Reviews: Unlocked Mobile Phones. The data was originally proposed by PromptCloud, which contains over 400 thousand reviews of unlocked mobile phones sold on Amazon.com to find out insights with respect to reviews, ratings, price and their relationships. 
The columns of data including Product Name(string, The name of the Product), Brand Name(string, Name of the parent company.), Price (number, Price of the product. Max: 2598, Min: 1.73, Mean: 226.86), Rating (number, Rating of the product ranging between 1-5), Reviews (string, Description of the user experience) and Review Votes (number, Number of people voted the review Min: 0, Max: 645, Mean: 1.50). 

Amazon Unlocked Phone Reviews Dataset from https://www.kaggle.com/PromptCloudHQ/amazon-reviews-unlocked-mobile-phones
