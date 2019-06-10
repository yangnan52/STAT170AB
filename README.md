# STAT170AB
  In our project, we are predicting the difference between Yelp's stars and Google's ratings for each individual business
## Datasets
  There are three mainly datasets.
  This project uses the [Yelp Open Dataset](https://www.yelp.com/dataset), which includes 5 files:

* `business.json`: Contains business data including location data, attributes, and categories.
* `review.json`: Contains full review text data including the user_id that wrote the review and the business_id the review is written for.
* `user.json`: User data including the user's friend mapping and all the metadata associated with the user.
* `checkin.json`: Checkins on a business.
* `tip.json`: Tips written by a user on a business. Tips are shorter than reviews and tend to convey quick suggestions.

The json files are too large to upload, so we create the sample dataset of them. 

  * review_sample.csv: A sample of all the reviews we have.
  * yelp_sample.csv: A sample of all the Yelp dataset
  * google_rating.csv: A sample of all the Google dataset

## Codes
  We separate all the codes into five ipynb files. They are google_api.ipynb, yelp_clean.ipynb, data_visualization.ipynb, LDA.ipynb and machine_learning.ipynb. 
  * google_api.ipynb: contains the codes crawling the ratings and reviews of each restaurant from Google by using the Google Places API.
  * yelp_clean.ipynb: contains the codes doing the data cleaning and preprocessing for the yelp dataset. 
  * data_visualization.ipynb: contains the codes of plotting data distribution and relationship between attributes and target values.
  * LDA.ipynb: contains the codes of running the text reviews into LDA model. 
  * machine_learning.ipynb:  contains all the codes running three different models, including Linear Regression, Random Forest Regressor and Gradient Boosting Regressor. 

