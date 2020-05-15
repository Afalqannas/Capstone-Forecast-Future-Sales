### Problem Statement

We are provided with daily historical sales data.
The task is to forecast the total amount of products sold in every shop for the test set.
Note that the list of shops and products slightly changes every month. Creating a robust model that can handle such situations is part of the challenge.



### Data
- The data from kaggle competition : Predict Future Sales
- datasets link: https://www.kaggle.com/c/competitive-data-science-predict-future-sales/data

### Data Description

- Our data contains information about sales in different Russian shops, also each shop sell different items or provide different services, in different cities.

### Data Dictionary

|Feature|Dataset|Description|
|-------|---|---|
|ID|test|an Id that represents a (Shop, Item) tuple within the test set.| 
|Shop_id|df_shops/test/df_sales_train0|unique identifier of a shop.| 
|item_id|df_items/test/df_sales_train0|unique identifier of a product.| 
|item_category_id |df_catog/df_sales_train0/df_items|unique identifier of item category.| 
|item_cnt_day|df_sales_train0|number of products sold. You are predicting a monthly amount of this measure.| 
|item_price|df_sales_train0|current price of an item.| 
|date|df_sales_train0|date in format dd/mm/yyyy.| 
|date_block_num|df_sales_train0|a consecutive month number, used for convenience. January 2013 is 0, February 2013 is 1,..., October 2015 is 33.| 
|item_name|df_sales_train0/df_items|name of item.|
|shop_name|df_sales_train0/df_shops|name of shop.|
|item_category_name|df_sales_train0/df_catog|name of item category.|



### Dependencies:
- NumPy
- IPython
- Pandas
- sklearn
- Matplotlib
- Seaborn



### Licenses
- Notebook : CC0: Public Domain
- datasets : go to this link https://www.kaggle.com/c/competitive-data-science-predict-future-sales/data