# StockSalesAnalysis
Exam patterns and trends in stock sales data

## Elementary Data Analysis
The distribution of each fields was plotted as shown below.
![image](https://user-images.githubusercontent.com/24922489/112740795-22874700-8f3d-11eb-82bf-7b66a1c0bc12.png)

## Clustering
K-means clustering methodology was used to classify stocks based on three factors: quantity, imbalance, Total Commission. KNN elbow plot was used to select the best number of clusters to apply. As shown in the plot below, 5 clusters are appropriate for the dataset, given the improvements after 5 is less significant.

![image](https://user-images.githubusercontent.com/24922489/112740811-3f237f00-8f3d-11eb-86d1-aa46e18ad2e5.png)


## Results

![image](https://user-images.githubusercontent.com/24922489/112740854-84e04780-8f3d-11eb-8dd3-1a7212cd69ae.png)
![image](https://user-images.githubusercontent.com/24922489/112740859-8ad62880-8f3d-11eb-94a5-c4b43076460c.png)

## Excel Dashboard
An interactive excel dashboard was then created for sharing the analysis results.
![image](https://user-images.githubusercontent.com/24922489/112741003-ece35d80-8f3e-11eb-9bd5-5a48f033256b.png)

For each stock (selected from menu on the right), 5 most correlated stock will be generated.
![image](https://user-images.githubusercontent.com/24922489/112741023-169c8480-8f3f-11eb-8cba-6c55cbff052e.png)

For each stock selected, the historical price and volatility will be plotted against S&P500.
![image](https://user-images.githubusercontent.com/24922489/112741077-7c890c00-8f3f-11eb-9458-a0e437f05032.png)

Clustering results are summarized below:
![image](https://user-images.githubusercontent.com/24922489/112741097-a2aeac00-8f3f-11eb-8601-fbd5355d069c.png)

## Key takeaways 
- Qualcomm, Walt Disney, Motorola Solutions have strongest growth momentum. However, Qualcomm have above average VaR.
- Communication services, Information Technology, Financials, and Materials on average have positive return.
- Most stocks in Semiconductor sector shown bearish look except for Qualcomm and AMD.
- Strong correlation observed between Semi-conductor stocks including: SWKS, AVGO, TXN, NVDA, ADI.
- Strong correlation observed between diversified banks stocks including: C, BCA.
- Strong correlation observed between IT stocks including: Adobe Systems, Visa, Microsoft, mastercard.
- Indentified 2 high commission stock groups with different level of trade imbalance.


