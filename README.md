# sao_paulo_apartments

# Pricing Factors in Neighborhoods of Different Social Classes

## Project Motivation:

This project aims to address several key questions regarding the factors that influence apartment prices in different regions. Firstly, we will explore the role that location plays in determining apartment prices. By analyzing apartments in peripheral areas and central regions of São Paulo, we will gain insights into how location impacts pricing decisions.

Additionally, we will investigate the variables associated with apartments in different areas. We will examine variables such as unit price, usable area, number of bedrooms, and number of suites to understand the characteristics of apartments in the outskirts and central parts of the city. By comparing these variables, we can identify any notable differences between the two regions.

Moreover, we will analyze the factors that have a greater influence on pricing apartments in central regions. By examining variables such as unit price, usable area, number of bedrooms, and number of suites, we can determine which factors carry more weight in determining the prices of apartments in desirable locations.

By addressing these questions, this project aims to provide valuable insights into the dynamics of apartment pricing in different regions and shed light on the factors that significantly impact the real estate market.

## Findings
Cluster 1: Apartments in peripheral areas, further away from the city center, showed that the number of bathrooms emerged as the predominant factor in determining apartment prices. Buyers or tenants in these areas value apartments with a greater number of bathrooms, indicating a preference for larger, more functional living spaces.

Cluster 0: Apartments in central regions, closer to the city center, revealed that the number of bathrooms is not as influential. Instead, the unit price and usable area play a more significant role in pricing. Higher unit prices and larger usable areas are associated with apartments in desirable locations, showcasing luxurious features and reflecting their premium value.

## Insights
Location Matters: The location of an apartment significantly impacts its pricing. Peripheral areas prioritize practicality and space (reflected by the number of bathrooms), while central areas focus on location, quality, and overall desirability (reflected by unit price and usable area).

Tailoring Strategies: Stakeholders in the real estate market can benefit from understanding these differences to tailor their strategies based on the specific clusters. This enables them to cater to the preferences and needs of potential buyers or tenants in different social classes.

## Usage
To replicate this analysis or delve deeper into the findings, please refer to the code and dataset available in this repository. The code provides a comprehensive understanding of the clustering process and the importance of different factors in determining apartment prices.

Feel free to explore the code and dataset, and don't hesitate to reach out if you have any questions or need further assistance.


## Libraries Used

The following libraries were used in this project:

- pandas: A powerful data manipulation library for data analysis.
- matplotlib.pyplot: A plotting library for creating visualizations in Python.
- sklearn.cluster.KMeans: A library for performing K-means clustering, a popular unsupervised learning algorithm.
- sklearn.metrics.silhouette_score: A metric to evaluate the quality of clustering based on the silhouette coefficient.
- seaborn: A data visualization library built on top of matplotlib, providing additional aesthetic and statistical features.
- warnings: A library for handling warning messages in Python.

To install the required libraries, you can use the following command:

```shell
pip install pandas matplotlib scikit-learn seaborn
```

## File desciption

Analysis.ipynb: Jupyter Notebook with code and analysis for the project.
dados_wgs.xlsx: Excel spreadsheet containing raw data for apartment listings in São Paulo.

## Resolution

You can fin the study in this link: https://medium.com/@joaoalberto.sequeira/what-influences-pricing-in-neighborhoods-of-different-social-classes-d9e29a703542

Data source: https://www.kaggle.com/datasets/jlgrego/apartamentos-venda-na-cidade-de-sao-paulo-sp