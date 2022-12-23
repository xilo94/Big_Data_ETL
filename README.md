## Instructions
# Part 1
Upload the part_one_starter_code.ipynb into Google Colab and create a duplicate of this file.

Explore the Amazon Reviews Links to an external site.datasets and pick two datasets to perform ETL.

Rename each part_one_starter_code.ipynb file according to the dataset you are using. For example, if you are going to use the Video Game reviews Links to an external site.file, rename file, part_one_video_games.ipynb. Repeat the process for the duplicate file you created in Step 2.

# Extract the Data

Read in each dataset using the correct header and sep parameters.

Get the number of rows in the dataset.

# Transform the Data

For each dataset use the schema.sql file located in the Resources folder of the Starter_Code.zip file to create the four DataFrames as follows:

Create the "review_id_df" DataFrame with the appropriate columns and data types.

Create the "products_df" DataFrame that drops the duplicates in the "product_id" and "product_title columns.

Create the "customers_df" DataFrame that groups the data on the "customer_id" by the number of times a customer reviewed a product.

Create the "vine_df" DataFrame that has the "review_id", "star_rating", "helpful_votes", "total_votes", and "vine" columns.

Load the Data into an RDS Instance

Export each DataFrame into the RDS instance to create four tables for each dataset.

NOTE
This process can take up to 10 minutes for each. Ensure that everything is correct before uploading.

## Part 2
Recall that this part is completely optional; you can complete it as a way to challenge yourself and boost your new skills.

In Amazon's Vine program, reviewers receive free products in exchange for reviews. Amazon has several policies to reduce the bias of its Vine reviews Links to an external site..
