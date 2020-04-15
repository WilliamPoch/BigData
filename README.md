# BigData
Project code for Introduction to Big Data Analytics class. <br>
## Project 1: <br>
1. QUERY 1: Find for the most frequently used noun Ignore all articles, conjunctions, prepositions, adjectives, adverbs, only focus on nouns.). Consider including NLTK part-of-speech tagger to remove those. Here is an example https://stackoverflow.com/questions/24406201/how-do-i-remove-verbs-prepositions-conjunctions-etc-from-my-text/24406270

2. QUERY 2: Find news about things in Thailand You may filter posts which have “thai” in it. To be more accurate, provinces could be used. And find the popular nouns in those posts.
</a><br>
## Project 2: <br>
Tasks

1. Find the Amazon product data from http://jmcauley.ucsd.edu/data/amazon/ I am not telling you to download the datasets since they are gigantic.

a. For this project, use only “Small” subsets of experimentation.

b. The data is in JSON, not CSV. Find a way to import it to your RDD or DF.

2. A recommended framework is to work on it on a cloud platform. You can use either

o Apache Spark (on GCP)

o Python (on GCP, Kaggle, or local machine but requires download.)

· If you use Python, there are guidelines on how to work with the datasets on the webpage.

· For the development process, choose only 5 brands with at least 500 reviews. Each brand may produce various products and ranges in various categories. But in the final output, use as many brands as possible.

· Use technique in Porntrakoon and Moemeng (2017) to rate the trust degree of each brand. The paper uses multiple categories to calculate.

o Let’s use only rating and review for trust calculation.

· Perform sentiment analysis to obtain “positive”, “neutral”, or “negative”.

· Output of the process is in the following form (brand, trust, rating) Where trust is from your calculation and rating is the average rating for the brand.
