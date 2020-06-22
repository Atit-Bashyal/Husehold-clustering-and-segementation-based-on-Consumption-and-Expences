## Executive Summary


### Task Outline and Dataset

This project is conducted with two main objectives.
- The first objective of this project is to explore if Households in Nepal can be clustered meaningfully on the basis their average calorie consumption per month of various food-types. 
- The second objective is to use an Association Mining approach (Market Basket Analysis) for each of the clusters to extract baskets where individual food items  frequently bought together or grown together by households in each clusters identified. 

The dataset used for this project is derived form the national-level data collected from Nepal National living Standards Survey(NLSS) 2011. The survey includes Household Level information from 3373 households sampled from different regions of Nepal. Information on the consumption of different food items by each sampled household is present in Section 5 ("Food Expenses and Household Production") of the survey questionnaire. The survey questionnaire is included in Appendix A of this report.

## Method of approach
With regards to the objective, data mining is performed on the raw dataset in order to create a comprehensive and tidy dataset. The first dataset, built for clustering,the average monthly consumption (in calories) of different food-types is computed. These food-types include : grains/cereals, pulses/lentils, poultry/dairy, oil/fat, vegetables, fruits, meat/fish and sugar. \\\\
After the clustering , the monthly average share of expenses on purchasing and expenses saved by using home-grown produce for each cluster is explored. For this purpose, data mining is again preformed in the raw dataset to extract information on individual household's monthly expenses(due to purchase for consumption)and saving(due to home-grown consumption) and cluster averages are computed .\\\\
Finally in order to find associations between different food items that are purchased or grown together, the dataset is transformed into the correct format so that it can be analyzed.  For each clusters identified, the raw dataset is used to build 2 new sub-sets( for purchase and home production) where each row represents an household and each column represents a food-item.\\\\
The results from each objective discussed above are then subsequently displayed using meaningful visualisations. Ultimately, a summary of the key insights obtained from the data are discussed in the conclusion of this report.


PDF CONTAINS FULL REPORT
