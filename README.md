# Machine Learning Project - Predicting Twitter Authors

As part of my final project for my Intro to Machine Learning course, my team and I set out to build a model that was trained to recognize the unique 
style of twitter authors. We decided specifically to analyze the twitter style of all 100 United States Senators. 
becuase we reasoned that this more specific data set would emphasize recognizing author style over simply recognizing topics. 

We leveraged the Twitter Developer API to scrape the 500 most recent tweets of all 100 US Senators, one-hot encoded the n most common words in the vocabulary of the dataset, and fed the cleaned data into 5 different machine learning models.

Our results were very promising, with our best models able to perform 45-50 times baseline (meaning that a baseline guess would result if 1% accuracy, while our models classified novel data with 45-50% accuracy).
