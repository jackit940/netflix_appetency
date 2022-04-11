# Kaggle competution

# Title : Netflix appetency

<img src='https://play-lh.googleusercontent.com/0rgPYj0GwZ6txpYZrzoMdhwzqg7vY6C9B-Ol7jlaz-Ox2rgpD4Tr82ZgDqkirrEohbGm'>

Link : https://www.kaggle.com/c/netflix-appetency


### Goal : Identifu consumers willing to subscribe to NEtflix according to their appetite
    
### Evaluation : AUC

<h2>Metric:</h2>

The metric used is AUC

<h2>Data:</h2>

* train.csv - the training set. it consists of an id column, the customers features, and a target column: target.
* test.csv - the test set. it consists of everything in train.csv except target.
* sample_submission.csv - a sample submission file in the correct format target=1 means that the customer subscribes to Netflix

For reasons of confidentiality, the data is anonymized and augmented.

Recommending similar products (apparel) to the given product (apparel) in any e-commerce websites. 

### Statement

-  Product recommendations are the alternative way of navigating through the online shop. Showing similar products to the user which user is searching for.


### Objective: 
- The recommendation engine, uses information about 1,80,000 products and each product will have multiple features named.
- We will try multiple techniques using text/title and image to recommend similar products/items


Each product/item has 19 features in the raw dataset out of these 19 features, we will be using only 6 features 

1. asin  ( Amazon standard identification number)
2. brand ( brand to which the product belongs to )
3. color ( Color information of apparel, it can contain many colors as   a value ex: red and black stripes ) 
4. product_type_name (type of the apperal, ex: SHIRT/TSHIRT )
5. medium_image_url  ( url of the image )
6. title (title of the product.)
7. formatted_price (price of the product)
