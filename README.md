# Amazon_Vine_Analysis
<!-- Analysis of review bias by Amazon Vine users using PySpark, Jupyter Notebook / Google Colab -->
## Project Background
The client SellBy participates in Amazon's Vine Program[^1], which is an invite-only group of buyers (Vine Voices) that receive free products from companies like SellBy in exchange for impartial reviews.  SellyBy has access to approximately 50 datasets of Amazon Reviews, and has requested an assessment of any review bias any single one of these datasets.  

[^1]: "About Amazon Vine". [https://sellercentral.amazon.com/help/hub/reference/external/92T8UV339NZ98TN?ld=SDUSSOADirect](https://sellercentral.amazon.com/help/hub/reference/external/92T8UV339NZ98TN?ld=SDUSSOADirect).

## Purpose
The purpose of this project is to determine if there is any bias toward favorable reviews from Vine members in the Amazon Video Games dataset.

## Resources
### Data Sources & Bespoke Code
1. [Amazon Video Game Reviews](https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz) [^2]
2. [Amazon_Reviews_ETL.ipynb](Amazon_Reviews_ETL.ipynb) [^3]

[^2]: "Amazon Review Data Sets". [https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt).  
[^3]: Google CoLab Notebook

### Software & CDNs
***Table 1: Software & Library Versions***
| Software | Version |
| :--- | :---: |
| pgAdmin | 6.8 |
| PostgreSQL | 11.16 |
| PostgreSQL JDBC | 4.2 / 42.2.16 |
| Python | 3.7.13 |
| Spark | 3.3.0 |
| Visual Studio Code | 1.70.2 |


# Results 
Using bulleted lists and images of DataFrames as support, address the following questions:
- How many Vine reviews and non-Vine reviews were there?
- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

<details><summary>View Screenshot of Final Map</summary>
  <p>
  <img src="images/challenge_map.png">
  </p>
</details>

# Summary 
In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.
