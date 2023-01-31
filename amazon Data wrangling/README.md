# Read Me

This Jupyter Notebook performs an exploratory data analysis on a dataset of pet product reviews. The data consists of reviews of pet products such as toys, food, and leashes, including the reviewer's ID, the product ASIN, the reviewer's name, the review text, and the overall rating.

## The following methods and steps were used in the analysis:

- Data cleaning and preprocessing: The data was loaded into the notebook, and any missing or irrelevant data was removed.
- Exploratory Data Analysis (EDA): The distribution of the overall ratings and the most common words used in the reviews were visualized using histograms and word clouds, respectively.
- Sentiment Analysis: The sentiment of each review was determined using the TextBlob library, which uses a pre-trained sentiment model. The overall sentiment for each product was visualized using bar plots.
- Further Analysis: Further analysis was performed to see the correlation between helpfulness and overall rating, and to see if the sentiment of a review affects its helpfulness.
- Conclusion: Based on the results of the analysis, a conclusion was drawn regarding the most helpful and highly rated pet products.

## Data

The Amazon Product Review dataset contains reviews, product information, and links related to Amazon products. It covers a span of 18 years, from May 1996 to July 2014, and contains a total of 142.8 million reviews. The dataset includes the following details:

- Product reviews (including ratings, text, and helpfulness votes)
- Product metadata (descriptions, category information, price, brand, and image features)
- Links between products (also viewed/also bought graphs)
- For those using the dataset for a class project or similar purpose, smaller subsets of the data are available for experimentation. However, if larger files are needed, one will need to contact the owner of the dataset for access.

## Data source is [this](http://jmcauley.ucsd.edu/data/amazon/index_2014.html)
