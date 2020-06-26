# Amazon reviews multilingual UK dataset


This project was divided into 4 tasks:
1. __Data Processing__ 
2. __Classification__ 
3. __Regression__ 
4. __Recommender Sytstems__
    1. Similarity matching
    2. Predictions
    3. Recommendations on Test set
    
## The Data

For this project I will be doing on amazon reviews dataset. The list of such dataset repository can be found [here.](https://s3.amazonaws.com/amazon-reviews-pds/readme.html)
This dataset is a set of multiple Product reviews bought in UK on amazon. This dataset is of size ~333 MB, so its a mid-range dataset.

### DATA COLUMNS:
    marketplace       - 2 letter country code of the marketplace where the review was written.
    customer_id       - Random identifier that can be used to aggregate reviews written by a single author.
    review_id         - The unique ID of the review.
    product_id        - The unique Product ID the review pertains to. In the multilingual dataset the reviews
                    for the same product in different countries can be grouped by the same product_id.
    product_parent    - Random identifier that can be used to aggregate reviews for the same product.
    product_title     - Title of the product.
    product_category  - Broad product category that can be used to group reviews 
                    (also used to group the dataset into coherent parts).
    star_rating       - The 1-5 star rating of the review.
    helpful_votes     - Number of helpful votes.
    total_votes       - Number of total votes the review received.
    vine              - Review was written as part of the Vine program.
    verified_purchase - The review is on a verified purchase.
    review_headline   - The title of the review.
    review_body       - The review text.
    review_date       - The date the review was written.

### DATA FORMAT
    Tab ('\t') separated text file, without quote or escape characters.
    First line in each file is header; 1 line corresponds to 1 record.
